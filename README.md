# Blank AngularJS project feat. UI Router

An empty Grunt-running setup including:

![](https://img.shields.io/badge/updated-june_1st_2018-green.svg)
![](https://img.shields.io/badge/grunt-1.0.2-ED8024.svg)
![](https://img.shields.io/badge/browserify-v5.3.0-pink.svg)
![](https://img.shields.io/badge/angularJS-v1.7.0-D00027.svg)
![](https://img.shields.io/badge/ui--router-v1.0.18-yellow.svg)
![](https://img.shields.io/badge/jquery-v3.3.1-005FAD.svg)
![](https://img.shields.io/badge/lodash-v4.17.10-3554FF.svg)

# Using this repo

### Initialize an `npm` project for use with Grunt

In the root:

```bash
npm init -y
```

`-y` says yes to every question `npm init` would otherwise ask you.

### Install necessary `npm` modules

These are listed as dependencies in `package.json` already.

```bash
npm install
```

_Note_: To use Angular and UI Router, you must copy the below minified JavaScript files into the `dist` folder. This is to minimize misery during deployment.

### Run the server

```bash
hs -o
```

### File structure

```
root
 |--assets
 |   |--css
 |   |
 |   |--js
 |   |   |--ctrl
 |   |   |--data
 |   |   |--factory
 |   |   |--main.js
 |   |   `--router.js
 |   |
 |   |--sass
 |   |   |
 |   |   `--style.scss
 |   |
 |   `--partials
 |
 |--dist
 |   |--angular.min.js
 |   |--angular-ui-router.min.js
 |   `--bundle.js
 |
 |--.gitignore
 |--Gruntfile.js
 |--package.json
 `--index.html
```