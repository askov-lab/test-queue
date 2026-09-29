# test-queue

This repository is a test project.

## CI

The `check` job passes when `ci-status` contains `pass`. Any other content fails
the job. `check` is a required status check on `main`.

PRs merge into `main` through a merge queue. The queue runs `check` again on
each merge group before it merges.
