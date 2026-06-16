<!-- markdownlint-disable-file MD033 -->

# Project

Project Description

## Todo

- [ ] GitHub Actions
  - [ ] `ci.yml` -- luau-lsp analyze and lune tests on push/PR
  - [ ] `release.yml` -- builds and creates a GitHub Release on tag
  - [ ] `publish.yml` -- runs `wally publish` on release
- [ ] Repository Docs
  - [ ] `CONTRIBUTING.md` -- branching, commit style, how to run CI locally, etc.
  - [ ] `SECURITY.md`
  - [ ] `.github/PULL_REQUEST_TEMPLATE.md`
  - [ ] `.github/ISSUE_TEMPLATE` -- bug report + feature request

## In Progress

- [ ] Lune Scripts
  - [ ] `.lune/build.luau`
  - [ ] `.lune/ci.luau` -- chains format-check -> tests
- [ ] Testing
  - [ ] Add `tests/` directory with an example spec
  - [ ] Add `.lune/test.luau` as the test runner

## Done ✓

- [x] Update Rojo `default.project.json`
- [x] Configure VitePress `config.mts`
- [x] Setup GitHub Actions for building docs
- [x] Sync vsc extensions and settings
  - [x] Extensions
  - [x] Settings
- [x] Toolchain
  - [x] Add `lune`
  - [x] Add `stylua` CLI
  - [x] Add `luau-lsp` CLI
  - [x] Add `wally-package-types`
- [x] Create `stylua.toml` configuration
