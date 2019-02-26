# test-module

## Project setup

# Package.json set up

```
{
"name": "jb3-test-web-component",
"version": "0.5.0",
"private": false,
"main": "./dist/test-web-component.common.js",
"scripts": {
"serve": "vue-cli-service serve",
"build": "vue-cli-service build",
"build-bundle": "vue-cli-service build --target lib --name test-web-component ./src/components/TestWebComponent.vue",
"lint": "vue-cli-service lint"
},
"files": [
"dist/*",
"src/*",
"public/*",
"*.json",
"*.js"
],
```

# Npm commands for build/bundle

```
npm run build-bundle
npm publish --access public
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
