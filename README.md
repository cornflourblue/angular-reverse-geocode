angular-reverse-geocode
=======================

AngularJS reverse geocoding directive


###Demo

To see a demo and further details go to http://jasonwatmore.com/post/2014/02/15/AngularJS-Reverse-Geocoding-Directive.aspx

###Installation

Install using bower: `bower install angular-reverse-geocode`

Alternatively download the code and include the angular-reverse-geocode.js file in your page.

Add the 'angularReverseGeocode' directive as a dependency of your AngularJS application:

```javascript
angular.module('myApp', ['angularReverseGeocode']);
```

###Usage

To use add a reverse-geocode tag to your page with attributes containing lat and long coordinates, e.g:

```html
<reverse-geocode lat="40.730885" lng="-73.997383"></reverse-geocode>
```