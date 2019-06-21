# tsconfig

This is the shared TypeScript configuration for my projects.

## Install

Install the package using NPM:

```sh
yarn add --dev @samuelmeuli/tsconfig
```

## Usage

Create the `tsconfig.json` file in your project root:

```json
{
  "extends": "@samuelmeuli/tsconfig"
}
```

The default configuration can be overridden or extended:

```json
{
  "extends": "@samuelmeuli/tsconfig",
  "compilerOptions": {
    "module": "ES6"
  }
}
```
