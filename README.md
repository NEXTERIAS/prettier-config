# prettier-config

Prettier configuration for NEXTERIAS

## Usage

### Use `prettier` field in `package.json`

```json
{
  "name": "@nexterias/ultimate-package",
  "prettier": "@nexterias/prettier-config"
}
```

### Override configuration

```js
module.exports = {
  ...require('@nexterias/prettier-config'),
  jsxSingleQuote: true,
}
```

## Run Prettier

```sh
npx prettier -w .
```
