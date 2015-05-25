# Nebbula Objarray module

This is part of Nebbula project. It's a node tree visitor. Add an object to an array between each element.

## Usage

```javascript
var o = require('nebbula-objarray');
var a = objarray([14, 25, 36], 'zaaz');

// [14, 'zaaz', 25, 'zaaz', 36]
console.log(a)
```