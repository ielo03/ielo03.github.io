# <my-username>.github.io

## Workflow highlights

- Conventional commits required for every change; PRs are validated via **commitlint** using `@commitlint/config-conventional`.
- **google-github-actions/release-please-action** infers versions and updates `CHANGELOG.md` from commit history, then publishes GitHub Releases.
- GitHub Pages deploys automatically from `main` using the official configure/upload/deploy workflow.
