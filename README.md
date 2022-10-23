# typescript-starter

[![codecov](https://codecov.io/gh/iwharris/typescript-starter/branch/master/graph/badge.svg)](https://codecov.io/gh/iwharris/typescript-starter)
[![Build](https://github.com/iwharris/typescript-starter/actions/workflows/ci.yaml/badge.svg)](https://github.com/iwharris/typescript-starter/actions/workflows/ci.yaml)

Boilerplate repo for personal Typescript projects

## Components

| Component/Framework                                            | Purpose                | Comments                                                                   |
| -------------------------------------------------------------- | ---------------------- | -------------------------------------------------------------------------- |
| [Jest](https://jestjs.io/)                                     | Test Framework         | Using [ts-jest](https://github.com/kulshekhar/ts-jest) for JIT compilation |
| [Prettier](https://prettier.io/)/[ESLint](https://eslint.org/) | Code style & linting   |
| [GitHub Actions](https://github.com/features/actions)          | Continuous Integration |
| [Codecov](https://codecov.io/)                                 | Code coverage tracking |

## Usage

### Compile

```bash
# Compile typescript to dist/
npm run compile

# Compile in watch mode
npm run watch
```

### Lint

```bash
# Check for style issues
npm run prettier

# Automatically fix style issues
npm run prettier:fix
```

### Test

```bash
# Run test suite
npm test

# Generate a coverage report
npm run test:coverage
```

### CI/CD

To publish a new version to npm:

```bash
npm version patch # or minor, or major
git push
git push --tags
```
