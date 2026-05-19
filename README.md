# DriftlessAF example repository

This repository is wired up to be monitored and improved by the DriftlessAF
agentic framework.

It uses the example reconciler bot [github-pr-validator](https://github.com/driftlessaf/go-driftlessaf/tree/main/examples/github-pr-validator/) to validate the PR title and description.

If the label `driftlessaf/autofix` is applied, the example reconciler bot
[github-pr-autofix](https://github.com/driftlessaf/go-driftlessaf/tree/main/examples/github-pr-autofix)
updates the PR title and description automatically.