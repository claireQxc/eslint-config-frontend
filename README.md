# eslint-config-zhizu

This package provides ZHIZU's base JS .eslintrc as an extensible shared config.

## Usage

### eslint-config-zhizu

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package
```sh
npm install --save-dev eslint-config-zhizu eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "zhizu"
}
```

### eslint-config-zhizu/es5

For some legacy project using es5.

First, install this package
```sh
npm install --save-dev eslint-config-zhizu eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "zhizu/es5"
}
```

### eslint-config-zhizu/react
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-zhizu eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
Then add following contents to your .eslintrc file
```
{
  "extends": "zhizu/react"
}
```

### eslint-config-zhizu/vue
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-zhizu eslint babel-eslint eslint-plugin-vue
```
Then add following contents to your .eslintrc file
```
{
  "extends": "zhizu/vue"
}
```

### eslint-config-zhizu/mini-program
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-zhizu eslint eslint-plugin-wxml
```
Then add following contents to your .eslintrc file
```
{
  "extends": "zhizu/mini-program"
}
```

## License
MIT