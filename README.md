# eslint-config
Opinionated ESLint config to use on various and numerous TypeScript repos

## Usage
### Install
```sh
yarn add -D @lsagetlethias/eslint-config
```

### Config
```js
// .eslintrc.js
{
    extends: ['@lsagetlethias'],
}
```

## Deps
### `@typescript-eslint/parser`
```js
// .eslintrc.js
{
    parser: '@typescript-eslint/parser',
    parserOptions: {
        project: ['./tsconfig.json', './tsconfig.eslint.json'],
        sourceType: 'module',
    },
}
```

## License
[MIT](./LICENSE)