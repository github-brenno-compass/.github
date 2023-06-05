# Compass Github

Hello, welcome to the Compass Github Super App.

This document presents all the available repositories for development. Additionally, we have some necessary patterns for feature development. So, stay tuned.

## Repository

### Pull Request

To make a Pull Request, make sure your project is following the Clean Code standards. You can also run `swiftlint lint` in your terminal and fix any errors found.

### CI

PRs are validated by a series of implemented Actions:

1. Swiftlint
2. Build
3. Code coverage tests
4. Documentation **(Release only)**

### Tests

The project was developed based on a Minimum Viable Project (MVP), which required prioritizing the integration of the Super App over test implementation.

However, the CI can detect when tests are missing and require them to be implemented before the PR is approved.

> UI tests were not considered for this project. If there are future discussions, it would be interesting to use snapshot-based UI tests.

## Features

The project is divided into the following features:

- [GithubKit](https://github.com/github-brenno-compass/GithubKit)
- [GithubUI](https://github.com/github-brenno-compass/GithubUI)
- [AuthenticationApp](https://github.com/github-brenno-compass/AuthenticationApp)
- [HomeApp](https://github.com/github-brenno-compass/HomeApp)
