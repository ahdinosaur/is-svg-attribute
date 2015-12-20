# is-svg-attribute

Check if an attribute name is supported by SVG specification.

code copied from (`virtual-hyperscript/svg-attribute-namespace`](https://raw.githubusercontent.com/Matt-Esch/virtual-dom/master/virtual-hyperscript/svg-attribute-namespace.js), .

## install

with [`npm`](https://www.npmjs.com), run

```
npm install --save ahdinosaur/is-svg-attribute#1.0.3
```

## usage

### `var isSvgAttribute = require('is-svg-attribute')`

### `isSvgAttribute(attributeName) -> Boolean`

## example

```
var isSvgAttribute = require('is-svg-attribute')

isSvgAttribute('cx') // true
isSvgAttribute('gradientTransform') // true
isSvgAttribute('class') // false
```
