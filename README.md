# ampcss

[![](https://img.shields.io/circleci/token/59737cd5e3b0bdf77733d6ef2a3a1ba5e198ff67/project/github/yukiyuriweb/ampcss/master.svg)](https://circleci.com/gh/yukiyuriweb/ampcss)
[![](https://img.shields.io/npm/dm/@yukiyuriweb/ampcss.svg)](https://npmcharts.com/compare/@yukiyuriweb/ampcss?minimal=true)
[![](https://img.shields.io/npm/v/@yukiyuriweb/ampcss.svg)](https://www.npmjs.com/package/@yukiyuriweb/ampcss)
[![license](https://img.shields.io/github/license/yukiyuriweb/ampcss.svg)](https://github.com/yukiyuriweb/ampcss/blob/master/LICENSE)

## Install

```bash
yarn add @yukiyuriweb/ampcss
```

## Usage

HTML:

```HTML
<link rel="stylesheet" href="https://unpkg.com/@yukiyuriweb/ampcss/dist/ampcss.css">
```

SCSS:

```css
@import 'path/to/node_modules/@yukiyuriweb/ampcss/sanitize';
@import 'path/to/node_modules/@yukiyuriweb/ampcss/variables';
@import 'path/to/node_modules/@yukiyuriweb/ampcss/basscss';
```

You can override `_variables.scss` by importing the scss file before importing `_basscss.scss`.
