# [Tawian Frontend](http://tawian.io/tawian-frontend/) [![npm package][npm-badge]][npm]

Simple CSS framework with a markdowny touch. Intended for developer facing applications.


## Usage

```html
<link rel="stylesheet" href="http://tawian.io/tawian-frontend/tawian-frontend.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Cousine:400,400i,700,700i">
```

or via [npm][npm]

```sh
npm install --save tawian-frontend typeface-cousine
```

And then, for example (as used in [curious-containers/cc-ui](https://github.com/curious-containers/cc-ui)):

```js
import 'tawian-frontend';
import 'typeface-cousine';
```

To use the icons, you have to place [icons.svg](https://raw.githubusercontent.com/tawian/tawian-frontend/master/icons.svg) at the root of your public path (or anywhere else and adjust the path in the icons svg code) or inline them in your HTML to make them work in Edge.


## Preview

[![Screenshot](https://raw.githubusercontent.com/tawian/tawian-frontend/master/screenshot.png)](http://tawian.io/tawian-frontend/)


## Build

```sh
npm run build

npm run watch  # builds continuously
```


## Credits

The project was inspired by [hack](https://github.com/egoist/hack).


[npm-badge]: https://img.shields.io/npm/v/tawian-frontend.svg?style=flat-square
[npm]: https://www.npmjs.org/package/tawian-frontend
