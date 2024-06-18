# Playwright Skeleton Project AVHB

This repo is to be used as a reference and learning opportunity to set up a playwright project from scratch.

Goals:
- [ ] Page object model and fixtures
- [ ] CI enabled runs on different platforms with GitHub Actions
- [ ] Dependency management with Renovate
- [ ] Publish Playwright reports with github pages
- [ ] Set up linting and styling

Potential extras:
- Pre-commit hooks for running tests

## Setup

### Pre-requisites

- `nvm`
- (optional) vscode

! Note: if using Linux, make sure to use Ubuntu, Fedora is not supported.

### Installation

1. install correct node version and enable it
    ```sh
    nvm install
    ```
    ```sh
    nvm use
    ```
2. install node dependencies
    ```sh
    npm ci
    ```

### Initialisation of the project

- create empty git repo
- add `.nvmrc`
- `npm init playwright@latest`
