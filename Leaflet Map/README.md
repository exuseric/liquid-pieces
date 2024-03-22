# Map Section for Shopify with Leaflet.js
This Shopify Liquid snippet allows you to easily embed a map on your storefront using Leaflet.js with optional google maps tiling.

It comes as is; adapt it per your needs.

## Features:
- Leverages Leaflet.js for map rendering.
- Utilizes metaobjects to store the location details for the map.
- Optionally displays the map using Google Maps tiles.

## Requirements:

1. Leaflet CSS and JavaScript from the CDN.
    - [LINK TO RESOURCE](https://leafletjs.com/examples/quick-start/)
2. (Optional) A Google Maps API Key. 
    - [LINK TO RESOURCE](https://developers.google.com/maps/documentation/javascript/get-api-key)
3. (Optional) Leaflet plugin to display Google maps baselayers.
    - [LINK TO  RESOURCE](https://gitlab.com/IvanSanchez/Leaflet.GridLayer.GoogleMutant)
4. Location Metaobjects

## Configuration
### Location Metaobjects
Create the following metaobject definitions

- Location ID: __*Single Line Text*__
- Title: __*Single Line Text*__
- Address 1: __*Single Line Text*__
- Address 2: __*Single Line Text*__
- Phone: __*Single Line Text*__
- Coordinates: __*Single Line Text*__
- Schedule: __*Multi-line Text*__

### Icons
Create an icon asset with the filename

Replace __*map-pin-icon.svg*__ in the code with the filename of your icon.