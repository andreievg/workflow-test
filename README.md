# Workflow Test Repository

This repository demonstrates workflow_run with artifacts and PR comments.

## How it works

1. When you open a PR, the "PR Workflow" runs
2. It saves the PR number and results to an artifact
3. The "Comment on PR" workflow triggers via workflow_run
4. It downloads the artifact and posts a comment on the PR

check
