# m5x2 `.github`

This repo exists only because of a GitHub-specific rule: a repo named exactly `.github` at the
org level is where GitHub looks for **default templates** — Issue templates and the Pull Request
template — for any repo in the org that doesn't define its own. It's not a regular project repo;
don't put code or docs here.

- **`ISSUE_TEMPLATE/`** — Bug Report and Feature Request forms, used automatically whenever anyone
  opens a new issue in any `m5x2` repo that has no template of its own.
- **`PULL_REQUEST_TEMPLATE.md`** — the default PR description template, same deal.

The actual process these templates support — how a ticket becomes a merged, deployed change — is
documented in `m5x2-software-docs`'s [`processes/feature-development.md`](https://github.com/m5x2/m5x2-software-docs/blob/main/processes/feature-development.md).
