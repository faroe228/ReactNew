ReactNew
======

Generates a React project skeleton. Inspired by `rails new`.

### Features
* Installs the following packages:
  * `babel-core`
  * `babel-loader`
  * `babel-preset-es2015`
  * `babel-preset-react`
  * `flux`
  * `react`
  * `react-dom`
  * `react-router`
  * `webpack`
* Creates `webpack.config.js` with sourcemap
* Creates `index.html` with entry point
* Creates initial `{PROJECT_NAME}.jsx` component
* Creates folders for `js` and `css`
* Runs `webpack --watch`

### Installation

```bash
brew tap timhwang21/react
brew install react
```

### Usage
```bash
react new PROJECT_NAME
```