# themegrill/workflows

Shared reusable GitHub Actions workflows for ThemeGrill repos. Contains no secrets;
callers pass them in.

- `pr-build-zip.yml`: builds a testable ZIP on PRs and comments the download link.
- `copilot-review-on-comment.yml`: requests a Copilot review from a PR comment.
- `scripts/preview-link.mjs`, `config/preview-link-repos.json`: used by `pr-build-zip.yml`.
