# Rocketseat ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
yarn add -D eslint @joel-luis/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@rocketseat/eslint-config/react"
  // "extends": "@joel-luis/eslint-config/node"
  // "extends": "@joel-luis/eslint-config/next"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
