<img align="right" src="https://raw.github.com/cliffano/save-changes-action/main/avatar.jpg" alt="Avatar"/>

[![Build Status](https://github.com/cliffano/save-changes-action/workflows/CI/badge.svg)](https://github.com/cliffano/save-changes-action/actions?query=workflow%3ACI)
[![Security Status](https://snyk.io/test/github/cliffano/save-changes-action/badge.svg)](https://snyk.io/test/github/cliffano/save-changes-action)
<br/>

Save Changes GitHub Action
--------------------------

GitHub Action for adding, committing, and pushing changes to a repository.

Usage
-----

Create a major release:

    jobs:
      build:
        steps:
          - uses: cliffano/save-changes-action@main
            with:
              message: 'Save changes'
