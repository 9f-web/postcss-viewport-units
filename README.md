# postcss-viewport-units

[![Build Status](https://travis-ci.org/springuper/postcss-viewport-units.svg?branch=master)](https://travis-ci.org/springuper/postcss-viewport-units)

Automatically append `content` property for [viewport-units-buggyfill](https://github.com/rodneyrehm/viewport-units-buggyfill).

## Install

```bash
$ npm install postcss-viewport-units
```

## Usage

See [PostCSS](https://github.com/postcss/postcss#usage) usage section for detail.

##### Options

`onlyCalc`(`Boolean`): if `ture`, only process `calc` values. it's `false` by default, which means, all values including `vw` `vh` `vmin` `vmax` are processed.

## License

MIT.
