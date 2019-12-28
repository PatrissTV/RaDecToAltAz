# RaDecToAltAz
This JavaScript class converts equatorial coordinates (Right ascension and Declination) into horizontal coordinates (Altitude and Azimuth).

##Installation
This project uses other libraries.
'''
npm i -S local-sidereal-time
'''
##Usage
In order to use it, import the RaDecToAltAz.js file first and then call the class.
'''
import RaDecToAltAz from './RaDecToAltAz.js'; 

let ra = 23.45; //hours
let dec = 16.6; //degrees
let lat = 1.4; //degrees
let lng = 34.1; //degrees

let coordinates = new RaDecToAltAz(ra,dec,lat,lng);
let alt = coordinates.getAlt();
let az = cordinates.getAz();

//alt and az are the requested results.
'''

You can also copy the code inside RaDecToAltAz instead of importing the class.
