# Ramda modules snippets (for Atom)

Import easily only the modules you need from [http://ramdajs.com/](http://ramdajs.com/).
Supports [Ramda 0.22.1v](http://ramdajs.com/).

Use Capitalize for Ramda function & Lowercase for vanilla Js function

## Examples
- CommonJS: typing `rav_always` will resolve to
```js
var Always = require('ramda/always');
```

- ES2015: typing `rai_always` will resolve to
```js
import Always from 'ramda/always';
```

for commented import

- CommonJS: typing `rav_always_doc` will resolve to
```js
//Always :: a -> (* -> a)'
var Always = require('ramda/always');
```

- ES2015: typing `rai_always` will resolve to
```js
//Always :: a -> (* -> a)'
import Always from 'ramda/always';`
```

## Installation
```
apm install ramda-modules-snippets
```
