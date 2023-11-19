# Renovate Bun

This repo has a CI which succeed when the `bun-types` dep's version matches the `packageManager` version in [package.json](./package.json), which allows renovate to [auto merge](./.github/renovate.json) if both version are updated in the same pull request.
