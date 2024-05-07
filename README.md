# Nectar UI

[![Nectar UI](https://raw.githubusercontent.com/staart/staart.js.org/master/assets/svg/ui.svg?sanitize=true)](https://staart.js.org/ui)

Nectar UI is a frontend starter for SaaS startups written in TypeScript and Vue using Nuxt.js. It has built-in landing pages, authentication, settings UIs, and more.

|              | Status                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Build        | [![GitHub Actions](https://github.com/staart/ui/workflows/Node%20CI/badge.svg)](https://github.com/staart/ui/actions) [![Travis CI](https://img.shields.io/travis/staart/ui?label=Travis%20CI)](https://travis-ci.org/staart/ui) [![Circle CI](https://img.shields.io/circleci/build/github/staart/ui?label=Circle%20CI)](https://circleci.com/gh/staart/ui) [![Azure Pipelines](https://dev.azure.com/staart/ui/_apis/build/status/staart.ui?branchName=master)](https://dev.azure.com/staart/ui/_build/latest?definitionId=1&branchName=master)                                                              |
| Dependencies | [![Dependencies](https://img.shields.io/david/staart/ui.svg)](https://david-dm.org/staart/ui) [![Dev dependencies](https://img.shields.io/david/dev/staart/ui.svg)](https://david-dm.org/staart/ui) ![Vulnerabilities](https://img.shields.io/snyk/vulnerabilities/github/staart/ui.svg)                                                                                                                                                                                                                                                                                                                       |
| Community    | [![Contributors](https://img.shields.io/github/contributors/staart/ui.svg)](https://github.com/staart/ui/graphs/contributors) [![GitHub](https://img.shields.io/github/license/staart/ui.svg)](https://github.com/staart/ui/blob/master/LICENSE) ![Type definitions](https://img.shields.io/badge/types-TypeScript-blue.svg) [![npm package version](https://img.shields.io/npm/v/@staart/ui)](https://www.npmjs.com/package/@staart/ui) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) |

Nectar UI is built to work with [Nectar](https://github.com/o15y/nectar), the backend starter for SaaS startups.

**⚠️ v2 BETA WARNING:** The master branch and all 2.x releases are currently in beta. For production, use v1.x instead on this commit tree: [`3c8e1e2`](https://github.com/staart/ui/tree/3c8e1e27fd41c7183a5da68f908a457f17ac2a19).

<table>
  <tbody>
    <tr>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/home.png">
      </td>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/login.png">
      </td>
    </tr>
    <tr>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/pricing.png">
      </td>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/profile.png">
      </td>
    </tr>
    <tr>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/members.png">
      </td>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/settings.png">
      </td>
    </tr>
    <tr>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/feedback.png">
      </td>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/billing.png">
      </td>
    </tr>
    <tr>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/2fa.png">
      </td>
      <td>
        <img alt="" src="https://raw.githubusercontent.com/staart/ui/3c8e1e27fd41c7183a5da68f908a457f17ac2a19/static/screenshots/api-key.png">
      </td>
    </tr>
  </tbody>
</table>

## Usage

Clone or fork this repository, then install dependencies:

```bash
yarn
