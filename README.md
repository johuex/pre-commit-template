# Pre-commit check on Merge(Pull) Requests

## Notes
    Examples in this repo not tested yet

* `github_versions` -- templates for GitHub repos
    * `github_runner_version` -- for using GitHub runners
    * `self_hosted_version` -- for using on self-hosted runners
* `gitlab_version` -- templates for GitHub repos
* `Dockerfile` -- image for runners
* `Makefile` -- for easy building container


## Using
1. Build image (if required) with `make build`

#### For GitHub repos
2. Copy `.github` folder and `.pre-commit-config.yaml` to the root of your project

#### For GitHub repos
2. Copy `.gitlab-ci.yaml` and `.pre-commit-config.yaml` files to the root of your project
