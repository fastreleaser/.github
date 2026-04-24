# fastreleaser

[![Status](https://img.shields.io/badge/status-in%20development-orange)](https://github.com/fastreleaser/fastreleaser)

Draft release fast. Publish instantly. Keep main linear.

The fastreleaser keeps release work on `fastreleaser/<tag>` while a draft release is still mutable. `update` keeps that branch one commit ahead of the default branch, `upload` refreshes the draft release assets, and `yield` fast-forwards the default branch and publishes the release.

## Repositories

- [fastreleaser/fastreleaser](https://github.com/fastreleaser/fastreleaser): core CLI and release workflow automation, currently experimental
- [fastreleaser/fastreleaser-apache-template](https://github.com/fastreleaser/fastreleaser-apache-template): commit-1 source material for the fresh canonical repo
- [fastreleaser/ai-orc](https://github.com/fastreleaser/ai-orc): long-term workspace and baseline settings for AI agents and human contributors

## Defaults

This organization uses shared issue templates, pull request guidance, and community health files from this special `.github` repository. Individual repositories may override them when they need repo-specific behavior.
