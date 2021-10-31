# elr-scss-layout

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-layout.svg?style=flat)](https://www.npmjs.com/package/elr-scss-layout)

some scss mixins for layout

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-layout --save
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

SEE LICENSE IN LICENSE.md
