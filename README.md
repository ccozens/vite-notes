# Vite + React + TypeScript + Airbnb + Husky = 🔥

1. This began life as a minimal template for [Vite + React + TypeScript](https://github.com/alessandropisu/vite-react-ts-minimal-template).
2. I added [material-ui](mui/com/material-ui): `npm install @mui/material @emotion/react @emotion/styled`
3. Set up husky pre-commit hooks, as per [this tutorial](https://javascript.plainenglish.io/catch-typescript-errors-in-nextjs-before-building-your-app-df129682ee5c)
4. 

## Features

- 🦾 Up to date libraries version and their features
- 🔎 Pre-configured and extensible ESLint configuration without wrong and unused rules designed for old React versions
- 💅 Pre-configured and extensible Prettier configuration
- 🔬 Git hooks for code formatting and linting pre-commit

## Usage

```bash
npx degit alessandropisu/vite-react-ts-minimal-template my-app

cd my-app

# Required if you want a repository and work with Git hooks
git init

yarn install

yarn dev
```

## Available commands

Run in development mode

```bash
  yarn dev
```

Create production build

```bash
  yarn build
```

Run ESLint linting

```bash
  yarn lint
```

Run Prettier formatting

```bash
  yarn format
```

Run TypeScript compiling

```bash
  yarn compile
```

Serve production build locally

```bash
  yarn preview
```

## Resources

- [Vite](https://github.com/vitejs/vite)
- [Airbnb JS Style Guide](https://github.com/airbnb/javascript)
- [Airbnb React Style Guide](https://github.com/airbnb/javascript/tree/master/react)
- [Husky](https://github.com/typicode/husky)

## License

[MIT](https://choosealicense.com/licenses/mit/)
