# eslint-config-thinkdot

## Install

```sh
npx install-peerdeps --dev eslint-config-thinkdot
```

## Usage

In your `.eslintrc.js`:

```tsx
module.exports = {
  extends: ["thinkdot"],
  parserOptions: {
    project: "./tsconfig.json",
  },
};
```

## License

MIT
