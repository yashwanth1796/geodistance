
## What is this?

To calculate distance between two latitudes and longitudes

## Installing

```sh
$ npm install geodistance

```
## Building bundled/minified version (for AMD, etc)

First run `npm install` to get all of the dependencies, and then run `make`:

```sh
$ npm install
$ make
```

The bundled and minified files will be in the generated `build` directory.

## Getting Started

var distance = require('geodistance');
```
var latLong1 = {
lat: '',
lng: ''
}
var latLong2 = {
lat: '',
lng: ''
}
var calDistance = distance(latLong1, latLong2)
