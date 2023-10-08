# Eslint + Prettier configuration package example

## Setup

Add the config and all its peer dependencies
`yarn add -D eslint-config-will @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier prettier typescript`

Add this to your package json scripts

```
"scripts": {
    "lint": "eslint src",
    "lint:fix": "eslint --fix src",
    "format": "prettier --check src",
    "format:write": "prettier --write src"
}
```
