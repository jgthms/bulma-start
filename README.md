# Start package for [Bulma](http://bulma.io)

Tiny npm package that includes the `npm` **dependencies** you need to **build your own website** with Bulma.

<a href="http://bulma.io"><img src="https://raw.githubusercontent.com/jgthms/bulma-start/master/bulma-start.png" alt="Bulma: a Flexbox CSS framework" style="max-width:100%;" width="600" height="315"></a>

## Install

```sh
npm install bulma-start
```
_or_

```sh
yarn add bulma-start
```

## What's included

Among the `npm` dependencies included in `package.json` are:

* <code>[bulma](https://github.com/jgthms/bulma)</code>
* <code>[node-sass](https://github.com/sass/node-sass)</code> to compile your own Sass file
* <code>[postcss-cli](https://github.com/postcss/postcss-cli)</code> and <code>[autoprefixer](https://github.com/postcss/autoprefixer)</code> to add support for older browsers
* <code>[babel-cli](https://babeljs.io/docs/usage/cli/)</code>, <code>[babel-preset-env](https://github.com/babel/babel-preset-env)</code> and <code>[babel-preset-2016](https://github.com/babel/babel/tree/master/packages/babel-preset-es2016)</code> for compiling ES6 JavaScript files

Apart from `package.json`, the following files are included:

* `.babelrc` configuration file for [Babel](https://babeljs.io/)
* `.gitignore` common [Git](https://git-scm.com/) ignored files
* `index.html` this HTML5 file
* `src/scss/main.scss` a basic SCSS file that **imports Bulma** and explains how to **customize** your styles, and compiles to `dist/css/main.css`
* `src/js/main.js` an ES6 JavaScript that compiles to `dist/js/main.js`

## Copyright and license

Code copyright 2018 Jeremy Thomas. Code released under [the MIT license](https://github.com/jgthms/bulma-start/blob/master/LICENSE).
