# Changelog

Notable changes in each spur-board release, newest first. A breaking change lists what changed and how to migrate the config under **BREAKING CHANGES**; the versioning policy is in [CONTRIBUTING.md](CONTRIBUTING.md#versions-and-the-changelog). Releases before this file, and any release not listed here, are on the [GitHub releases page](https://github.com/AnDeVerin/spur-board/releases).

## [0.164.2](https://github.com/AnDeVerin/spur-board/compare/v0.164.1...v0.164.2) (2026-11-23)

### Bug Fixes

* **deps:** update runtime dependencies ([#868](https://github.com/AnDeVerin/spur-board/issues/868)) ([bdf4fbd](https://github.com/AnDeVerin/spur-board/commit/bdf4fbdb526bba6b5f5dd2341e5a1b07a31196fb))

## Upgrade notes from earlier releases

### 0.58.0

Change a dedicated worker column executor to `role: orchestrator`. For operator execution use the literal `orchestrator: operator`, rather than the name of an operator project. Curator executors remain supported.
