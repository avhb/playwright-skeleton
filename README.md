# Playwright Skeleton Project AVHB

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/avhb/playwright-skeleton/playwright.yml?branch=main&logo=playwright&label=Playwright%20Tests)

[Renovate Dashboard](https://developer.mend.io/github/avhb/playwright-skeleton)

This repo is to be used as a reference and learning opportunity to set up a playwright project from scratch.

Goals:
- [ ] Page object model and fixtures
- [ ] CI enabled runs on different platforms with GitHub Actions
- [x] Dependency management with Renovate
- [ ] Publish Playwright reports with github pages
- [ ] Set up linting and styling

Potential extras:
- Pre-commit hooks for linting, styling and running tests

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

### Renovate configuration

- install github app and give it access to your repo: https://github.com/apps/renovate
- onboarding: https://docs.renovatebot.com/getting-started/installing-onboarding/#repository-onboarding
- dashboard: https://developer.mend.io/github/avhb
