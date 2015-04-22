[![Build Status](https://secure.travis-ci.org/Nytramr/bespoke-theme-simple-slide.png?branch=master)](https://travis-ci.org/Nytramr/bespoke-theme-simple-slide)

# bespoke-theme-simple-slide

A simple theme for [Bespoke.js](http://markdalgleish.com/projects/bespoke.js) &mdash; [View demo](http://Nytramr.github.io/bespoke-theme-simple-slide)

## Download

Download the [production version][min] or the [development version][max], or use a [package manager](#package-managers).

[min]: https://raw.github.com/Nytramr/bespoke-theme-simple-slide/master/dist/bespoke-theme-simple-slide.min.js
[max]: https://raw.github.com/Nytramr/bespoke-theme-simple-slide/master/dist/bespoke-theme-simple-slide.js

## Usage

This theme is shipped in a [UMD format](https://github.com/umdjs/umd), meaning that it is available as a CommonJS/AMD module or browser global.

For example, when using CommonJS modules:

```js
var bespoke = require('bespoke'),
  simpleSlide = require('bespoke-theme-simple-slide');

bespoke.from('#presentation', [
  simpleSlide()
]);
```

When using browser globals:

```js
bespoke.from('#presentation', [
  bespoke.themes.simpleSlide()
]);
```

## Package managers

### npm

```bash
$ npm install bespoke-theme-simple-slide
```

### Bower

```bash
$ bower install bespoke-theme-simple-slide
```

## Credits

This theme was built with [generator-bespoketheme](https://github.com/markdalgleish/generator-bespoketheme).

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
