# turf-flip

[![build status](https://secure.travis-ci.org/Turfjs/turf-flip.png)](http://travis-ci.org/Turfjs/turf-flip)

turf flip module


### `turf.flip(input)`

Takes a GeoJSON object of any type and flips all of its coordinates
from `[x, y]` to `[y, x]`.


### Parameters

| parameter | type    | description          |
| --------- | ------- | -------------------- |
| `input`   | GeoJSON | input GeoJSON object |


### Example

```js
var saudiArabia = turf.point([20.566406, 43.421008]);

//=saudiArabia

var serbia = turf.flip(saudiArabia);

//=serbia
```


**Returns** `GeoJSON`, a GeoJSON object of the same type as `input` with flipped coordinates

## Installation

Requires [nodejs](http://nodejs.org/).

```sh
$ npm install turf-flip
```

## Tests

```sh
$ npm test
```

