# React Webpack Typescript Starter
> Minimal starter with hot module replacement (HMR) for rapid development.

* **[React](https://facebook.github.io/react/)** (17.x)
* **[Webpack](https://webpack.js.org/)** (5.x)
* **[Typescript](https://www.typescriptlang.org/)** (4.x)
* **[Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)** ([React Hot Loader](https://github.com/gaearon/react-hot-loader))
* Production build script (Webpack)
* Image loading/minification ([Image Webpack Loader](https://github.com/tcoopman/image-webpack-loader))
* [SASS](http://sass-lang.com/) support
* Code linting ([ESLint](https://github.com/eslint/eslint)) and formatting ([Prettier](https://github.com/prettier/prettier))
* Test framework ([Jest](https://facebook.github.io/jest/))

## Installation
1. Clone/download repo
2. `yarn install` (or just `npx tsx-app <your-app-name>` for npm
---

**All commands**

Command | Description
---|---
`clean`|`rm dist/bundle.js`
`build-dev`|`webpack --mode development`
`build-prod`|`webpack --mode production`
`start`|`webpack serve --hot --mode development`
**Note**: replace `yarn` with `npm` in `package.json` if you use npm.

## See also
* [Team website](https://kmoz.dev)
