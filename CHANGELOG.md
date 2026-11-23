# Changelog

Notable changes in each spur-board release, newest first. A breaking change lists what changed and how to migrate the config under **BREAKING CHANGES**; the versioning policy is in [CONTRIBUTING.md](CONTRIBUTING.md#versions-and-the-changelog). Releases before this file, and any release not listed here, are on the [GitHub releases page](https://github.com/AnDeVerin/spur-board/releases).

## [0.165.1](https://github.com/AnDeVerin/spur-board/compare/v0.165.0...v0.165.1) (2026-11-23)

### Bug Fixes

* **testkit:** [#866](https://github.com/AnDeVerin/spur-board/issues/866) refuse Vitest runs started in a package dir ([#886](https://github.com/AnDeVerin/spur-board/issues/886)) ([4ed056c](https://github.com/AnDeVerin/spur-board/commit/4ed056c4b6265ad5c1e83b60d28abe0ef352a705))

## [0.165.0](https://github.com/AnDeVerin/spur-board/compare/v0.164.4...v0.165.0) (2026-11-23)

### Features

* **web:** [#811](https://github.com/AnDeVerin/spur-board/issues/811) open a project block in a block panel from the inbox ([#881](https://github.com/AnDeVerin/spur-board/issues/881)) ([dfddaa1](https://github.com/AnDeVerin/spur-board/commit/dfddaa1211dcaccfeb1c7b1062f30e932a7bf80f))

### Bug Fixes

* **web:** [#883](https://github.com/AnDeVerin/spur-board/issues/883) accept cross-site top-level navigations to the page ([#885](https://github.com/AnDeVerin/spur-board/issues/885)) ([5c20ec3](https://github.com/AnDeVerin/spur-board/commit/5c20ec3c28fb4dff63dd420a76cce5f42c6e5991))

## [0.164.4](https://github.com/AnDeVerin/spur-board/compare/v0.164.3...v0.164.4) (2026-11-23)

### Bug Fixes

* **web:** [#817](https://github.com/AnDeVerin/spur-board/issues/817) list the folded Backlog closest to Dev first ([#882](https://github.com/AnDeVerin/spur-board/issues/882)) ([0ce2116](https://github.com/AnDeVerin/spur-board/commit/0ce2116f375176382b2f3e73da82c83ccd4619ad))

## [0.164.3](https://github.com/AnDeVerin/spur-board/compare/v0.164.2...v0.164.3) (2026-11-23)

### Bug Fixes

* **web:** [#809](https://github.com/AnDeVerin/spur-board/issues/809) give the warn chip text the attention text token ([#878](https://github.com/AnDeVerin/spur-board/issues/878)) ([97eb403](https://github.com/AnDeVerin/spur-board/commit/97eb403b42d4ed5a6bc8762e8e3fcb6ec13eb1f9))

## [0.164.2](https://github.com/AnDeVerin/spur-board/compare/v0.164.1...v0.164.2) (2026-11-23)

### Bug Fixes

* **deps:** update runtime dependencies ([#868](https://github.com/AnDeVerin/spur-board/issues/868)) ([bdf4fbd](https://github.com/AnDeVerin/spur-board/commit/bdf4fbdb526bba6b5f5dd2341e5a1b07a31196fb))

## Upgrade notes from earlier releases

### 0.58.0

Change a dedicated worker column executor to `role: orchestrator`. For operator execution use the literal `orchestrator: operator`, rather than the name of an operator project. Curator executors remain supported.
