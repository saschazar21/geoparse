# GeoParse Canon GPS-Tracks

Canon's newer GPS-enabled SLRs are able to produce GPS-Tracks in the GPRMC format of [NMEA specification](http://www.gpsinformation.org/dale/nmea.htm).
To make them useable in JavaScript applications, information like  
```
$GPRMC,123519,A,4807.038,N,01131.000,E,022.4,084.4,230394,003.1,W*6A
```
needs to be parsed in a standardized format like [GeoJSON](http://geojson.org).