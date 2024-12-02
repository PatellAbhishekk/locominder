# Locominder

![mockup](mockup.png)

## About

Locominder is a tool for creating and managing a local development environment for a [Locomotive CMS](https://github.com/locomotivemtl/locomotive-cms) project.

## Installation

```bash
pnpm create vite@latest locominder
pnpm install
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

In index.css file :
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Usage

```bash
pnpm run dev
```

This will create a new project in the current directory.

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://raw.githubusercontent.com/PatellAbhishekk/Portfolio/refs/heads/main/LICENSE)
