# node-typescript-template

Write your node app with typescript immediately!

## What's included

The following programs are included to help you bootstrap your app development:
- configured node.js & typescript development environment
- jest testing framework (https://facebook.github.io)
- linter ([tslint](https://palantir.github.io/tslint/))
- [VSCode](https://code.visualstudio.com/) workspace configuration

## Prerequisites

Please ensure the following programs have been installed on your system before proceeding:
- node.js (https://nodejs.org/en/)
- yarn package manager (https://yarnpkg.com/en/)

## Usage

Clone
```bash
$ git clone https://github.com/raibima/node-typescript-template my-app
```
Reconfigure git
```bash
$ cd my-app
$ rm -rf .git
$ git init
```
Install dependencies
```bash
$ yarn
```
Watch ts changes
```bash
$ yarn watch
```
Start app in dev mode (with nodemon)
```bash
$ yarn dev
```
