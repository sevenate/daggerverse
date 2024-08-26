# daggerverse

Modules for dagger.io

## Conventions

- [Semantic Versioning 2.0.0](https://semver.org/)
- [Conventional Commits 1.0.0](https://www.conventionalcommits.org)
  - enforced by [commitlint](https://commitlint.js.org/) and extended to the following supported  types from [karma-runner](http://karma-runner.github.io/6.4/dev/git-commit-msg.html) and [angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#revert):
    - `feat:` for a new feature for the user, not a new feature for build script. Such commit will trigger a release bumping a MINOR version.
    - `fix:` for a bug fix for the user, not a fix to a build script. Such commit will trigger a release bumping a PATCH version.
    - `perf:` for performance improvements. Such commit will trigger a release bumping a PATCH version.
    - `docs:` for changes to the documentation.
    - `style:` for formatting changes, missing semicolons, etc.
    - `refactor:` for refactoring production code, e.g. renaming a variable.
    - `test:` for adding missing tests, refactoring tests; no production code change.
    - `ci:` for updating build configuration, development tools or other changes irrelevant to the user.
    - `revert:` for reverting previous commit(s).
  - The first line cannot be longer than 72 characters and should be followed by a blank line. The type and scope should always be lowercase.
