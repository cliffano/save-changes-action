<!-- BEGIN:AVATAR -->
![Avatar](avatar.jpg)
<!-- END:AVATAR -->

<!-- BEGIN:BADGES -->
[![Build Status](https://github.com/cliffano/save-changes-action/workflows/CI/badge.svg)](https://github.com/cliffano/save-changes-action/actions?query=workflow%3ACI)
[![Security Status](https://snyk.io/test/github/cliffano/save-changes-action/badge.svg)](https://snyk.io/test/github/cliffano/save-changes-action)
<!-- END:BADGES -->

# Save Changes GitHub Action

GitHub Action for adding, committing, and pushing changes to a repository.

## Usage

Save local changes with commit message 'Save changes':

```yaml
jobs:
  build:
    steps:
      - uses: cliffano/save-changes-action@main
        with:
          message: 'Save changes'
          push_changes: 'true'
```

When running tests, set push_changes to false so the action does not push commits or tags to remote repository.

## Colophon

<!-- BEGIN:DEVELOPERS_GUIDE -->
[Developer's Guide](https://cliffano.github.io/developers-guide-github-action.html)
<!-- END:DEVELOPERS_GUIDE -->

<!-- BEGIN:BUILD_REPORTS -->
Build reports:

* [Lint report](https://cliffano.github.io/save-changes-action/lint/yamllint.txt)
* [Test report](https://cliffano.github.io/save-changes-action/test/act.txt)
* [API documentation](https://cliffano.github.io/save-changes-action/doc/action-docs/index.html)

<!-- END:BUILD_REPORTS -->
