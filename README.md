# RaDecToAltAz
This JavaScript class converts equatorial coordinates (Right ascension and Declination) into horizontal coordinates (Altitude and Azimuth).

## Installation

```
npm i -S radectoaltaz
```

## Usage

In order to use it, import the RaDecToAltAz.js file first and then call the class. Variables alt and az are the corresponding values for altitude and azimuth.

```
let radectoaltaz = require('radectoaltaz');

let ra = 23.45; //hours
let dec = 16.6; //degrees
let lat = 1.4; //degrees
let lng = 34.1; //degrees

let coordinates = new radectoaltaz(ra,dec,lat,lng);
let alt = coordinates.getAlt();
let az = coordinates.getAz();

console.log(alt,az);

```
