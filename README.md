# react-ts-starter

[Create React App](https://github.com/facebook/create-react-app) does not have a few build steps which are necessary such as linting files, configuring prettier and enabling coverage reports

## Additional Scripts

In the project directory, you can run:

### `yarn lint`

Runs all the linting steps for files in src folder with extensions js, jsx, ts, tsx, json, css and scss.

### `yarn lint:fix`

Runs lint command with --fix flag which tries to automatically fix the lint problems.

### `yarn test:watch`

Runs tests in watch mode

### `yarn coverage`

Runs test cases with --collect-coverage flag. You can set minimum code coverage limits in jest.coverageThreshold.global property in package.json

### `yarn coverage:watch`

Runs coverage in watch mode

### How does it work

I have used the following references for setting up this project

- linting typescript, javascript, tsx and jsx - [Using ESLint and Prettier in a TypeScript Project](https://dev.to/robertcoopercode/using-eslint-and-prettier-in-a-typescript-project-53jb)
- linting css and scss - [styelint](https://stylelint.io/)
  - By default stylelint does not work well with prettier. To fix this problem we use recommended configuration from [stylelint-prettier](https://github.com/prettier/stylelint-prettier)
