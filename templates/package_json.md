# `package.json`

```json
{
  "name": "ajs",
  "version": "1.0.0",
  "description": "",
  "main": "src/index.js",
  "scripts": {
    "start": "webpack serve --mode development",
    "build": "webpack --mode production",
    "watch": "tsc -w",
    "lint": "eslint .",
    "lint:fix": "eslint . --fix",
    "test": "jest --coverage",
    "show:dist": "live-server dist",
    "show:coverage": "live-server coverage/lcov-report"
  },
  "repository": {
    "type": "git",
    "url": "git+link.git"
  },
  "author": "You",
  "license": "ISC",
  "bugs": {
    "url": "link/issues"
  },
  "homepage": "link#readme",
  "devDependencies": {
    "@babel/cli": "^7.25.6",
    "@babel/core": "^7.25.2",
    "@babel/preset-env": "^7.25.4",
    "@eslint/js": "^9.11.1",
    "@stylistic/eslint-plugin-js": "^2.8.0",
    "babel-jest": "^29.7.0",
    "babel-loader": "^9.2.1",
    "css-loader": "^7.1.2",
    "eslint": "^9.11.1",
    "globals": "^15.10.0",
    "html-loader": "^5.1.0",
    "html-webpack-plugin": "^5.6.0",
    "jest": "^29.7.0",
    "mini-css-extract-plugin": "^2.9.1",
    "style-loader": "^4.0.0",
    "webpack": "^5.95.0",
    "webpack-cli": "^5.1.4",
    "webpack-dev-server": "^5.1.0"
  },
  "dependencies": {
    "core-js": "^3.38.1"
  }
}
```