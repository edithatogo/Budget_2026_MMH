# Contributing to Budget_2026_MMH

Contributions should improve the organization, provenance, and reproducibility of this budget-analysis and source-document collection.

## Before you start

Read the [README](README.md) and inspect existing source files before adding material. Identify the question addressed, document issuer, publication date, and version. Check for duplicate copies and explain whether a new file is an original source, a corrected version, or a derived analysis.

Search existing issues and the repository history to avoid duplicating work. Describe substantial proposals before implementation, and use repository issue templates when available. Keep corrections in focused branches so they are easy to inspect.

For bug reports, include the affected version or commit, environment, minimal reproduction, expected and actual behavior, and sanitized diagnostics. For feature requests, explain the use case and intended outcome.

## Development and validation

This repository currently contains documents and spreadsheets rather than a software package with a defined test runner. For source additions, verify that the file opens, matches its stated title and issuer, and has a stable source reference. Preserve original files separately from extracts, summaries, and transformed tables.

For analysis, record the input versions, units, time period, assumptions, and calculation steps. Make any new code or spreadsheet transformations reproducible and provide independently checked example calculations. Distinguish source statements from interpretation and identify uncertainty or missing evidence. Record actual document, spreadsheet, or script validation instead of claiming a generic test suite passed.

Update affected documentation and examples alongside behavior changes. Add a focused regression case for a bug fix where executable tests are appropriate. Record checks that were not run and the reason.

## Submitting a contribution

Pull requests are currently disabled in this repository. Prepare a focused branch from the current `main` branch and retain a compare link so the proposed changes can be inspected. Use the existing issue tracker for non-sensitive proposals and clarification. Follow the repository's configured integration process; do not enable pull requests or bypass checks as part of an ordinary contribution. If pull requests are enabled later, target `main`. Keep unrelated changes separate.

Include:

- The problem, proposed change, and resulting behavior.
- Related issues or existing track references.
- Exact validation commands or inspection steps, results, and limitations.
- Compatibility implications and any data or dependency provenance.

Inspect the complete diff before submission. Required automated checks must pass before merge. Follow the existing repository and account policies; this guide does not introduce a second-person approval requirement or relax existing checks.

## Security and sensitive information

Follow the [account security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Report vulnerabilities privately through GitHub's **Report a vulnerability** option if available. Otherwise request a private reporting contact without disclosing the vulnerability publicly. Keep credentials, personal data, and unredacted logs out of commits, issues, and examples.

## Licensing and conduct

Respect the [existing license](LICENSE) and preserve third-party notices. Submit only material you are entitled to contribute, and document unclear permissions before adding third-party content. Follow the [account code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md). This guide adds no CLA, mandatory sign-off, or relicensing condition.

## Reference guidance

- [GitHub contributor guidelines](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [OpenSSF Best Practices criteria](https://www.bestpractices.dev/en/criteria)
