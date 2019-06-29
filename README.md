# Dot JS

A simple JS function that reads an object and retrieves the values from it using the dot notation.

Import the lib. You need the download the **storage.js** file. Currently there is no npm repository.
```js
import dot from './dot';
```

## Usage

Get value
```js
// dot(object, string)
dot({a: 1, b: {c: 2, d: {e: 2}}}, 'b')
```

Will return
```js
{c: 2, d: {e: 2}}
```

## MIT

[MIT](http://opensource.org/licenses/MIT)
