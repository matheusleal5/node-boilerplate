# Node Boilerplate | 🐙 Matheus Pereira Leal

## Techs

- [Node.js](https://nodejs.org/en/) - Evented I/O for the backend
- [TypeScript](https://www.typescriptlang.org/) - JavaScript with syntax for types

## Description

This is a boilerplate for Node.js with TypeScript designed with Eslint and Prettier for code standardization and formatting and Husky, Lint Staged and Git Commit Msg Linter for commit standardization.

The purpose of this boilerplate is to standardize all code formatting of a team of developers and ensure Test Driven Development (TDD) as a software development practice.

Furthermore, the boilerplate is fully flexible to follow any type of software architecture you want. However, I recommend for your projects the use of an architecture based on (Domain Driven Design) DDD and Clean Architecture.

## Installation

Node.js Borleiplate requires [Node.js](https://nodejs.org/) v16+ (LTS) to run.

Clone this repository with HTTPS or SSH:
```sh
# HTTPS
git clone https://github.com/matheusleal5/node-boilerplate.git
# SSH
git clone git@github.com:matheusleal5/node-boilerplate.git
```

Install all necessary dependencies inside the cloned directory:
```sh
# Using yarn
yarn
# Using npm
npm install
```

If you use npm, change yarn to npm run in:
```sh
.lintstagedrc
.husky/pre-push
```
and update scripts files for:
```sh
"test": "NODE_ENV=test jest --passWithNoTests --silent --noStackTrace --runInBand --no-cache",
"test:staged": "npm run test -- --findRelatedTests",
"test:ci": "npm run test -- --coverage",
```
Remember:
- Feel free to adapt the boilerplate to your project structure
- Don't forget to change the Jest settings for your use and the path of the dev and start scripts with your application's initialization file, for example: src/index.ts.

Finally, you can start developing with the architecture that suits you best!

## Contact me
Email: <contact@matheuspleal.com)><br>
[Site](https://matheuspleal.com)<br>
[LinkedIn](https://linkedin.com/in/matheuspleal/)<br>
[Instagram](https://instagram.com/matheuspleal)<br>
<br>
# 🐙
