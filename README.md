# @gmworks/eslint-config

gm works Eslint Config  

Common eslint config with optional support for [React](https://reactjs.org/), [JSX Accessibility](https://github.com/reactjs/react-a11y), [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html), and [Prettier](https://prettier.io/)

## Install

```sh
yarn add -D @gmworks/eslint-config
```

## Usage

eslint config

```js
{
  "extends": [
    "@gmworks/eslint-config", // Base file this should be included at the top.
    "@gmworks/eslint-config/typescript", // Add if you're using typescript.
    "@gmworks/eslint-config/react", // Add if you're using react.
    "@gmworks/eslint-config/prettier", // Add if you want prettier to format your code (recommended)
  ],
  "rules": {
    // Add custom rules and overrides here
  }
}
```
