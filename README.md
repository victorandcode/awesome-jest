# Awesome Jest [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> An awesome list of [Jest](https://facebook.github.io/jest/) packages and resources


## Contents

- [Packages](#packages)
  * [Matchers](#matchers)
  * [IDE](#ide)
  * [Linting](#linting)
  * [Runners](#runners)
  * [Reporters](#reporters)
  * [Results Processors](#results-processors)
  * [Environments](#environments)
  * [Snapshot](#snapshot)
  * [Migration](#migration)
  * [Library extensions](#library-extensions)
  * [Mocks](#mocks)
- [Resources](#resources)


## Packages

### Matchers

- [jest-extended](https://www.github.com/jest-community/jest-extended) Adds additional matchers to core API making it easy to test everything.
- [expect-more](https://github.com/JamieMason/expect-more/tree/master/packages/expect-more-jest) A huge library of test matchers for a range of common use-cases.
- [jest-axe](https://github.com/nickcolley/jest-axe) Custom Jest matcher for [aXe](https://axe-core.org/) for testing accessibility.
- [jest-enzyme](https://github.com/FormidableLabs/enzyme-matchers/tree/master/packages/jest-enzyme) An assertion library for enzyme.
- [jest-json-schema](https://github.com/americanexpress/jest-json-schema) JSON schema matcher.
- [expect-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/expect-puppeteer) Collection of matchers for Jest & Puppeteer.

### IDE

- [vscode-jest](https://www.github.com/jest-community/vscode-jest) Works out of the box Jest based testing in VS Code.
- [wallaby](https://github.com/wallabyjs/public/) The pinnacle of the idea of a test runner integrated into an editor.

### Linting

- [eslint-plugin-jest](https://www.github.com/jest-community/eslint-plugin-jest) ESLint plugin for Jest.

### Runners

- [jest-runner-eslint](https://www.github.com/jest-community/jest-runner-eslint) ESLint runner for Jest.
- [jest-runner-mocha](https://github.com/rogeliog/jest-runner-mocha) Mocha runner for Jest.
- [jest-runner-prettier](https://github.com/keplersj/jest-runner-prettier) Prettier runner for Jest.

### Reporters

- [jest-silent-reporter](https://github.com/rickhanlonii/jest-silent-reporter) A silent reporter for Jest.
- [jest-skipped-reporter](https://github.com/rickhanlonii/jest-skipped-reporter) Report skipped tests in Jest.

### Results Processors
- [jest-stare](https://github.com/dkelosky/jest-stare) Configurable HTML results processor for filtering, side-by-side snapshot diffs, API, and simple CLI.

### Environments

- [jest-environment-webdriver](https://github.com/alexeyraspopov/jest-webdriver) custom environment for WebDriver integration.
- [jest-environment-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/jest-environment-puppeteer) Puppeteer environment for Jest.

### Snapshot

- [snapshot-diff](https://www.github.com/jest-community/snapshot-diff) Takes two values, and return their difference as a string, ready to be snapshotted with toMatchSnapshot(). Especially helpful when testing the difference between different React component states.
- [jest-snapshots-svg](https://www.github.com/jest-community/jest-snapshots-svg) Take a React component tree, and render it into an SVG.
- [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) Take a snapshot test of an image buffer, and catch when the image changes over a threshold. Commonly used for visual regression testing.
- [enzyme-to-json](https://github.com/adriantoine/enzyme-to-json) Convert Enzyme wrappers to a format compatible with Jest snapshot testing.
- [jest-styled-components](https://github.com/styled-components/jest-styled-components) A set of utilities for testing Styled Components with Jest.

### Migration

- [jest-codemods](https://github.com/skovhus/jest-codemods) Makes it easy to migrate from other test runner and frameworks to Jest.

### Library extensions

- [testdouble-jest](https://github.com/testdouble/testdouble-jest) Support for [testdouble.js](https://github.com/testdouble/testdouble.js) for users of Jest.
- [jest-puppe-shots](https://github.com/macku/jest-puppe-shots) A Jest plugin for creating screenshots of [React](https://reactjs.org/) components with a little help of [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [jest-each](https://www.github.com/mattphillips/jest-each) Allows tests to be writen once with multiple rows of data supplied to run the test multiple times.
- [babel-jest-assertions](https://www.github.com/mattphillips/babel-jest-assertions) Babel plugin that automatically adds the number of assertions found in each test with `expect.assertions(n)` and `expect.hasAssertions()`.
- [jest-puppeteer](https://github.com/smooth-code/jest-puppeteer) A Jest preset that enables a ready-to-use environment to write integration tests using Puppeteer.
- [typescript-snapshots-plugin](https://github.com/asvetliakov/typescript-snapshots-plugin) Extends the TypeScript dev server to support hovering and jumping to a snapshot.

### Mocks

- [jest-fetch-mock](https://github.com/jefflau/jest-fetch-mock) Easily mock out `fetch` and set up responses, powered by [Jest mock functions](https://facebook.github.io/jest/docs/en/mock-functions.html).

## Resources

- [Jest cheat sheet](https://github.com/sapegin/jest-cheat-sheet).
- [React Jest workshop](https://github.com/kentcdodds/react-jest-workshop).


## Contribute

Contributions welcome! Read the [contribution guidelines](/CONTRIBUTING.md).


## License

[MIT](/LICENSE)
