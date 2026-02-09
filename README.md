<p align="center">
  <h1 align="center">react_basic_webpack_app</h1>
  <p align="center">
    A minimal React application with a custom Webpack setup — demonstrating manual bundling, Babel transpilation, and SCSS styling without Create React App.
  </p>
</p>

<p align="center">
  <a href="https://github.com/girijashankarj/react_basic_webpack_app"><img src="https://img.shields.io/github/last-commit/girijashankarj/react_basic_webpack_app?style=flat-square&logo=github" alt="last commit" /></a>
  <img src="https://img.shields.io/badge/React-16-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React 16" />
  <img src="https://img.shields.io/badge/Webpack-3-8DD6F9?style=flat-square&logo=webpack&logoColor=white" alt="Webpack 3" />
  <img src="https://img.shields.io/badge/Babel-ES2015-F9DC3E?style=flat-square&logo=babel&logoColor=black" alt="Babel" />
  <img src="https://img.shields.io/badge/SCSS-styling-CC6699?style=flat-square&logo=sass&logoColor=white" alt="SCSS" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs welcome" />
</p>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Scripts Reference](#scripts-reference)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

**react_basic_webpack_app** is an educational project that shows how to set up a React application from scratch using Webpack and Babel — without relying on Create React App. It demonstrates manual configuration of module bundling, JSX transpilation, SCSS compilation, and asset loading.

---

## Features

- **Custom Webpack config** — no CRA abstraction
- **Babel transpilation** — ES2015 + React JSX presets
- **SCSS support** — Sass compilation with mixins
- **Asset loading** — file-loader and url-loader for images
- **Watch mode** — auto-rebuild on file changes
- **Component-based** — DescriptionView and OperationsView components
- **Interactive demo** — text input + spinning React logo toggle

---

## Tech Stack

|                  | Details                              |
| ---------------- | ------------------------------------ |
| **Framework**    | React 16.2                           |
| **Bundler**      | Webpack 3.12                         |
| **Transpiler**   | Babel (ES2015 + React + Stage-2)     |
| **Styling**      | SCSS/Sass + CSS                      |
| **Dev Server**   | Webpack Dev Server 2.10              |

---

## Quick Start

```bash
git clone https://github.com/girijashankarj/react_basic_webpack_app.git
cd react_basic_webpack_app
npm install
npm start
```

Open `index.html` in your browser to see the bundled app.

### Watch mode

```bash
npm run garry
```

Webpack will watch for file changes and rebuild automatically.

---

## Project Structure

```
react_basic_webpack_app/
├── source/
│   ├── index.js                # Main entry point
│   ├── javascript/
│   │   ├── descriptionView.jsx # Description component
│   │   └── operationsView.jsx  # Operations component
│   └── stylesheet/
│       ├── mixin.scss          # SCSS mixins
│       ├── stylesheet_scss.scss# SCSS styles
│       ├── stylesheet_css.css  # CSS styles
│       └── reactjs_logo.png    # React logo asset
├── destination/
│   └── bundled.js              # Compiled bundle output
├── index.html                  # HTML entry point
├── webpack.config.js           # Webpack configuration
├── package.json
└── LICENSE                     # MIT License
```

---

## Scripts Reference

| Script    | Command                    | Description                     |
| --------- | -------------------------- | ------------------------------- |
| `start`   | `webpack`                  | Bundle the application          |
| `garry`   | `webpack --watch`          | Bundle with watch mode          |

---

## Contributing

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/my-feature`
3. **Make** your changes
4. **Commit** and open a Pull Request

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with discipline by <a href="https://github.com/girijashankarj">GarryTJ</a>
</p>
