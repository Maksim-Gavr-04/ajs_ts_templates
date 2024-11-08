# The `npm` commands and scripts in the `package.json`

**Важно**: для TypeScript.

---

## The `npm` commands

### `live-server`

```
npm i -D live-server
```

### `Babel`

```
npm i -D babel-jest @babel/core @babel/cli @babel/preset-env @babel/preset-typescript
```

```
npm i core-js@3
```

### `TypeScript`
```
npm i -D ts-jest typescript
```

```
npx tsc --init
```


### `ESLint`

```
npm i -D eslint typescript-eslint
```

```
npm init @eslint/config
```

```
npm i -D @eslint/js @types/eslint__js
```

```
npm i -D @stylistic/eslint-plugin
```

### `Webpack`

```
npm i -D webpack webpack-cli webpack-dev-server
```

```
npm i -D ts-loader babel-loader html-loader css-loader
```

```
npm i -D html-webpack-plugin mini-css-extract-plugin
```

### `Jest`

```
npm i -D jest @types/jest
```

```
npx ts-jest config:init
```

---

## Scripts in the `package.json`

```json
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
```