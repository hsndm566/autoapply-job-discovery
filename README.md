# AutoApply Job Discovery — Public ATS Adapter Subset

This repository preserves a narrow, source-attributed subset of public ATS adapters from [`ever-jobs/ever-jobs`](https://github.com/ever-jobs/ever-jobs), whose upstream repository declares the MIT License. GitHub denied creation of an upstream fork for the authenticated integration, so this is a **source-attributed derivative**, not a GitHub-network fork.

## Included public adapter packages

- Greenhouse
- Lever
- Workday
- SAP SuccessFactors
- Oracle Taleo

The upstream MIT `LICENSE` is retained in this repository. `.upstream-commit` records the upstream revision used for this subset.

## Explicit exclusions

This repository contains no LinkedIn adapter, Indeed adapter, proxy rotation, CAPTCHA handling, login or credential mechanism, application module, or browser-execution module. It is a reference and attribution subset for the policy-gated AutoApply Labs discovery service, not a deployed application executor.
