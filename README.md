# [TypeScript] [React] [Single-Page Application][spa]

## Installation

Install [`nvm`] by following the [Node Version Manager installation instructions](https://github.com/nvm-sh/nvm#installing-and-updating).

Install the [Node] version specified in [`.nvmrc`]:

```console
nvm install $(cat .nvmrc)
```

Switch to the [Node] version specified in [`.nvmrc`]:

```console
nvm use
```

**Note**: To ensure tools installed by [`nvm`] are used (rather than other versions of those same tools installed in, say, `/usr/bin`), make `$NVM_BIN` the first entry in `$PATH`.

[Install](https://yarnpkg.com/getting-started/install) [`yarn`]:

```console
corepack enable
yarn set version stable
yarn install
```

This installs [`yarn`] in `$NVM_BIN`.

Install the project's dependencies:

```console
yarn install
```

## Development

Launch the application in development mode:

```console
yarn dev
```

Lint with [ESLint]:

```console
yarn lint
```

Check for formatting errors with [Prettier]:

```console
yarn fmt
```

Correct formatting errors with [Prettier]:

```console
yarn fmt:fix
```

Generate an optimized build for production:

```console
yarn build
```

Launch the application in production mode (after running `yarn build`):

```console
yarn preview
```

[`nvm`]: https://github.com/nvm-sh/nvm
[`nvmrc`]: ./nvmrc
[`yarn`]: https://yarnpkg.com/
[ESLint]: https://eslint.org/
[Node]: https://nodejs.org/en
[Prettier]: https://prettier.io/
[React]: https://react.dev
[spa]: 
[TypeScript]: https://www.typescriptlang.org/
