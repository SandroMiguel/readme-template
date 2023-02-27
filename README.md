<img src="docs/assets/logo-readme-template.svg" width="100px" height="100px" alt="README template">

# readme-template

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

README.md template for my projects

## Table of Contents

1. [Installation](#installation)
1. [Usage](#usage)
1. [NodeJS scripts](#nodejs-scripts)
1. [Development](#development)
1. [Contributing](#contributing)
1. [Questions](#questions)
1. [Changelog](#changelog)
1. [License](#license)

## Installation

...

## Usage

...

## NodeJS scripts

- start - see [Development](#development)
- lint - see [Lint code](#lint-code)
- lint:fix - see [Fix linter errors](#fix-linter-errors)
- format - see [Format JavaScript](#format-javascript)
- format:php - see [format-php](#format-php)
- stylelint - see [Lint styles](#lint-styles)
- stylelint:fix - see [Lint and fix styles](#lint-and-fix-styles)
- test - see [JavaScript unit testing](#javascript-unit-testing)
- test:watch - see [JavaScript unit testing (watch mode)](#javascript-unit-testing-watch-mode)
- test:phpunit - see [PHP unit testing](#php-unit-testing)
- e2e - see [E2E testing](#e2e-testing)
- build - see [Production](#production)
- release - see [Release a new version](#release-a-new-version)
- sync:ubiquitous-components - see [Sync Ubiquitous Components](#sync-ubiquitous-components)
- sync:verum-php - see [Sync Verum PHP](#sync-verum-php)

## Development

Runs the app in the development mode.

Runs webpack and watches for changes.

```sh
yarn start
```

## Lint

### Lint code

```sh
yarn lint
```

### Fix linter errors

```sh
yarn lint:fix
```

### Format JavaScript

```sh
yarn format
```

### Format PHP

Example - format `User.uploadPhoto.php` file:

```sh
yarn run prettier ./requests/User.uploadPhoto.php --write
```

### Lint styles

```sh
yarn stylelint
```

### Lint and fix styles

```sh
yarn stylelint:fix
```

## Run tests

### JavaScript unit testing

```sh
yarn test
```

### JavaScript unit testing (watch for changes)

```sh
yarn test:watch
```

### PHP unit testing

```sh
yarn test:phpunit
```

### E2E testing

Run tests with UI

```sh
yarn e2e
```

## Production

Builds the app for production into the `public` folder.

```sh
yarn build
```

## Release a new version

```sh
yarn release
git push --follow-tags
```

## Utilities

### Sync Ubiquitous Components

```sh
yarn sync:ubiquitous-components
```

### Sync Verum PHP

```sh
yarn sync:verum-php
```

## Contributing

Want to contribute? All contributions are welcome. Please read the [contributing guide](CONTRIBUTING.md).

## Questions

If you have questions tweet me at [@sandro_m_m](https://twitter.com/sandro_m_m) or [open an issue](../../issues/new).

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
