# release-please-test

This repository is used as a test for Google's release-please and how it could be made to work with a git-flow based branching scheme.

## Solution

It creates separate PRs for `develop --> main` resp. `main --> develop`, so that it also correctly handles the cases for protected branches.
