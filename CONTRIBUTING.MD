# Contributing to this project

First off, thanks for taking the time to contribute! 🎉

When contributing to this repository, please first describe the change you wish to make [via an issue](https://github.com/cardano-foundation/veridian-docs/issues/new) before making a change.
Please note we have a [code of conduct](CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

## Issues and pull requests

### Bug reports

[Submit a bug report](https://github.com/cardano-foundation/veridian-docs/issues/new?assignees=&labels=&projects=&template=bug_report.yml&title=%5BBUG%5D+) using the provided template for bug reports. If the template does not fit your purpose start with a blank issue.

For bug reports, it's very important to fill in the information in the structure provided by the templates to help us analyzing the bug.

### Feature requests and ideas

[Submit a feature request](https://github.com/cardano-foundation/veridian-docs/issues/new?assignees=&labels=&projects=&template=feature_request.yml&title=%5BFEATURE%5D+) using the provided template for feature requests. If the template does not fit your purpose start with a blank issue but make sure the name starts with a "FEATURE" in square brackets.

### Creating a pull request

Thank you for contributing your changes by opening a pull requests! To get something merged we usually require:

- The pull request should successfully clear existing tests.
- ❗ Description of the changes - please follow the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/#specification) as we use it to automatically generate our CHANGELOG ❗This repository has a githook to ensure the use of conventional commits. To configure it run this command on the root of the project before creating your first commit:

```
make init
```

- Change is related to an issue (feature request or bug report) - ideally discussed beforehand
- Well-scoped - we prefer multiple PRs, rather than a big one