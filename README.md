# countries-cities 
A node module to get countries and their related cities.

## Example usage

``` javascript
var countries = require ('countries-cities').getCountries(); // Returns an array of country names.
var cities = countries.getCities(country_name); // Returns an array of city names of the particualr country.

