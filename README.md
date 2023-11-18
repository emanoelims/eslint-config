# Emanoel ESLint config

## What's included?

- Prettier
- Tailwind plugin

## Setup
### React (with Next.js)

Install dependencies:

```shell
npm i -D @emanoelims/eslint-config
```

Inside `.eslintrc.json`

```json
{
  "extends": [
    "@emanoelims/eslint-config", 
    "next/core-web-vitals"
  ]
}
```
