# Tawian Frontend

Simple CSS framework with a markdowny look. Based on [hack](https://github.com/egoist/hack).


## Usage

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/tawian/tawian-frontend/master/style.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Cousine:400,400i,700,700i">
```


## Look

![Screenshot](https://raw.githubusercontent.com/tawian/tawian-frontend/master/screenshot.png)


## Build

Simple

```sh
sass sass/index.scss --style compressed | postcss --use autoprefixer > css/style.css
```

With watcher

```sh
fswatch -o sass/* | xargs -n1 sh -c 'sass sass/index.scss --style compressed | postcss --use autoprefixer > css/style.css'
```
