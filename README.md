[update-readmes]   Mode: rewrite — migrating to template structure...
# immutable-linux-framework

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/immutable-linux-framework)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/immutable-linux-framework.git
cd immutable-linux-framework
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
The repository uses GitHub Actions for continuous integration and automation. Below are the workflows and their purposes:

- **build.yml**: Builds the project binaries for all supported architectures. No secrets required.
- **test.yml**: Runs automated tests using `vitest` for the JavaScript components and `go test` for Go components. No secrets required.
- **lint.yml**: Lints the codebase using ESLint for JavaScript and `golangci-lint` for Go. No secrets required.
- **deploy-book.yml**: Deploys the project documentation to the specified hosting service. Requires `DOCS_DEPLOY_TOKEN` secret.
- **mirror-artifacts.yml**: Synchronizes build artifacts to external storage. Requires `ARTIFACT_STORAGE_KEY` and `ARTIFACT_STORAGE_SECRET` secrets.
- **sync-to-gitlab.yml**: Mirrors the repository to GitLab. Requires `GITLAB_TOKEN` secret.
- **cleanup-branches.yml**: Deletes stale branches in the repository. No secrets required.
- **validate-config.yml**: Validates configuration files such as `go.mod` and `package.json`. No secrets required.

Refer to the `.github/workflows/` directory for detailed workflow configurations.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/immutable-linux-framework`](https://github.com/Interested-Deving-1896/immutable-linux-framework) and mirrored through:

```
Interested-Deving-1896/immutable-linux-framework  ──►  OpenOS-Project-OSP/immutable-linux-framework  ──►  OpenOS-Project-Ecosystem-OOC/immutable-linux-framework
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
| File | Description |
|---|---|
| [.gitlab/merge_request_templates/Default.md](https://github.com/Interested-Deving-1896/immutable-linux-framework/blob/main/.gitlab/merge_request_templates/Default.md) | GitLab MR template |
| [config/gitlab-subgroups.yml](https://github.com/Interested-Deving-1896/immutable-linux-framework/blob/main/config/gitlab-subgroups.yml) | GitLab subgroup map |
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/immutable-linux-framework/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
