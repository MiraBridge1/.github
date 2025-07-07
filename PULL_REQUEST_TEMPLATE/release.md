# 🏷️ Release Pull Request

## Summary

This PR prepares a new release of the template. The actual release is triggered automatically by pushing a Git tag (e.g.
`v1.0.0`).

## Changes

- [ ] Version bumped in `deno.json`
- [ ] Corresponding entry added to `CHANGELOG.md`

## Checklist

- [ ] This PR merges the `development` branch into `master` for release
- [ ] Changelog entry accurately reflects this release
- [ ] Version follows semantic versioning
- [ ] A Git tag (e.g. `vX.Y.Z`) will be pushed after merge
- [ ] The code passes `make check`
- [ ] The code passes CI checks
