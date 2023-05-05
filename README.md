## Bustracker

This code initializes a Google Map with the specified options and displays it on a webpage. It also retrieves bus location data from the MBTA API and adds markers to the map to indicate the location of the buses on the route. The addMarkers() function retrieves the data and updates the markers every 15 seconds, while the addMarker() function adds a new marker to the map. The getMarker() function retrieves an existing marker based on the bus ID, while the moveMarker() function updates the marker's position and icon when the bus location changes.


## Roadmaps

If you want to change the city displayed on the map in the provided code, you can do so by changing the center property in the myOptions object to the latitude and longitude coordinates of your desired city. You can find these coordinates by searching for your city on Google Maps and copying the coordinates from the URL. For example, if you want to display New York City instead of Boston, you can replace { lat:42.353350,lng:-71.091525} with { lat:40.712776,lng:-74.005974} in the myOptions object.

## Support

Support is not available at this time. 


## License

Copyright 2023 Alice McElyea

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
