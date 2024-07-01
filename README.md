 React + TypeScript + Vite
# BITCOINEX

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
This repository contains the initial setup and the final version of the Bitcoinex project, including the basic project structure, necessary images, and icons.

Currently, two official plugins are available:
## Overview

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
This project is a new project, Bitcoinex. The repository provides two branches:

## Expanding the ESLint configuration
1. **Initial Setup**: Provides the foundational structure and assets needed to build the full application.
2. **Final Version**: The completed application with all functionalities.

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:
## Getting Started

- Configure the top-level `parserOptions` property like this:
To get started with either the initial setup or the final version, follow these instructions:

`js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```
### Cloning the Repository

1. **Clone the Repository**:

    ```bash
    git https://github.com/AJnextlb/Bitcoinex.git
    cd Bitcoinex
    ```

### Initial Setup

2. **Switch to the `initial-setup` Branch**:

    ```bash
    git checkout initial-setup
    ```

3. **Install Dependencies**:

    ```bash
    npm install
    ```

4. **Run the Development Server**:

    ```bash
    npm run dev
    ```

5. **Open Your Browser**:

    Navigate to localhost to see the initial setup.

### Final Version

2. **Switch to the `final-version` Branch**:

    ```bash
    git checkout final-version

**Switch to the `final-version` Branch**:

    ```bash
    git checkout final-version
    ```

3. **Install Dependencies**:

    ```bash
    npm install
    ```

4. **Run the Development Server**:

    ```bash
    npm run dev
    ```

5. **Open Your Browser**:

    Navigate to localhost to see the final version of the application.

## Contact

For any inquiries, please contact me in Telegram: [Nikandr Surkov](https://t.me/btcexonsol).

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
