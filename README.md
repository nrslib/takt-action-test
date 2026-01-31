# takt-action-test

Test repository for [takt-action](https://github.com/nrslib/takt-action) CI/CD.

## Purpose

This repository is used to test the takt-action GitHub Action in a safe environment.

## How to Test

1. Create an issue
2. Comment `@takt run test` on the issue
3. takt-action will execute the test workflow
4. A PR should be created automatically

## Workflow

Uses the `test` workflow with `--pipeline` mode for fast execution.
