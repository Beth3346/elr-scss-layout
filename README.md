# Layout

[![npm version](http://img.shields.io/npm/v/elr-scss-layout.svg)](https://www.npmjs.org/package/elr-scss-layout)
[![CI](https://github.com/Beth3346/elr-scss-layout/actions/workflows/node.js.yml/badge.svg)](https://github.com/Beth3346/elr-scss-layout/actions/workflows/node.js.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-layout.svg?style=flat)](https://www.npmjs.com/package/elr-scss-layout)

some scss mixins for layout

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-layout
```

or

```sh
yarn add elr-scss-layout
```

### Reset Element

Removes margin, padding, and sets line-height to 1.

```scss
@include elr-reset-element;
```

### Reset Clearfix

Included for projects that need to use floats. In most cases using flexbox instead of floats is recommended.

```scss
@include elr-clearfix;
```

### Screen Reader Content

Hides content visually but makes it available for screen readers.

```scss
@include elr-screen-reader;
```

### Center Block

```scss
@include elr-center-block;
```

### Center Flex

Vertically and horizontally center content within a block.

```scss
@include elr-center-flex;
```

### Containers

```scss
@include elr-containers(
  $config: (
    max-width: 1024px,
  )
);
```

SEE LICENSE IN LICENSE.md
