# Contributing

Contributions are welcome! Please make sure your pull request adheres to the following guidelines.

## Inclusion criteria

An entry should:

- Be open-source, with a public repository (GitHub, GitLab, etc.)
- Be relevant to **wealth management, asset management, or estate planning** — portfolio construction, risk/performance analytics, market data access, quantitative finance, accounting/ledger, tax, actuarial/estate modeling, compliance/KYC/AML, or backtesting
- Be actively maintained, or be a widely-used, stable de facto standard even if development has slowed
- Be written in **Python, Go, or Rust**

Please don't add:

- Closed-source or SaaS-only products
- Personal toy projects with no adoption and no maintenance activity
- Duplicate entries already covered by a more actively-maintained fork (link the fork, not the abandoned original)

## Adding an entry

1. Add your entry to the appropriate category table in `README.md`, keeping rows alphabetized by package name within their language group.
2. Follow the existing row format:
   ```
   | Language | [Package](https://github.com/owner/repo) | ![Stars](https://img.shields.io/github/stars/owner/repo?style=flat-square) | One-line description |
   ```
3. Keep descriptions to a single, factual sentence — no marketing language.
4. If you're introducing a new category, add it to both the Table of Contents and as a new `##` section, and explain briefly what it covers.
5. If a language has no credible entries in a given category, leave a short note saying so rather than forcing in an off-topic package.

## Pull requests

- One logical change per pull request (e.g. "add X to Risk & Performance Analytics") is preferred over large batches, so each addition can be reviewed on its own merits.
- In the PR description, briefly explain why the package belongs in this list.
