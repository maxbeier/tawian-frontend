# [Tawian Frontend](http://tawian.io/tawian-frontend/) [![npm package][npm-badge]][npm]

Simple CSS framework with a markdowny look. Based on [hack](https://github.com/egoist/hack).


## Usage

```html
<link rel="stylesheet" href="http://tawian.io/tawian-frontend/tawian-frontend.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Cousine:400,400i,700,700i">
```

or via [npm][npm] (font still has to be added to the html)

```sh
npm install --save tawian-frontend
```


## Look

[![Screenshot](https://raw.githubusercontent.com/tawian/tawian-frontend/master/screenshot.png)](http://tawian.io/tawian-frontend/)


## Build

Simple

```sh
sass sass/index.scss --style compressed | postcss --use autoprefixer > tawian-frontend.css
```

With watcher

```sh
fswatch -o sass/* | xargs -n1 sh -c 'sass sass/index.scss --style compressed | postcss --use autoprefixer > tawian-frontend.css'
```


[npm-badge]: https://img.shields.io/npm/v/tawian-frontend.svg?style=flat-square
[npm]: https://www.npmjs.org/package/tawian-frontend
