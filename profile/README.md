# FastReleaser

Draft release fast. Publish instantly. Keep main linear.

FastReleaser keeps release work on `fastreleaser/<tag>` while a draft release is still mutable. `update` keeps that branch one commit ahead of the default branch, `upload` refreshes the draft release assets, and `yield` fast-forwards the default branch and publishes the release.

## Repositories

- [fastreleaser/fastreleaser](https://github.com/fastreleaser/fastreleaser): core CLI and release workflow automation

## Defaults

This organization uses shared issue templates, pull request guidance, and community health files from this special `.github` repository. Individual repositories may override them when they need repo-specific behavior.
