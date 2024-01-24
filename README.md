# GitHub Actions

[![CI/CD](https://github.com/pinjaalanne/jenkins/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/pinjaalanne/jenkins/actions/workflows/main.yml)

A simple Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
