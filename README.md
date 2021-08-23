# React Webpack Typescript Starter
> Minimal starter with hot module replacement (HMR) for rapid development.

* **[React](https://facebook.github.io/react/)** (17.x)
* **[Webpack](https://webpack.js.org/)** (5.x)
* **[Typescript](https://www.typescriptlang.org/)** (4.x)
* [Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)
* light Production build script (Webpack) with HtmlWebpackPlugin & BundleAnalyzerPlugin.

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
