# Aldes integration for Home Assistant

This integration allows Home Assistant to fetch and modify data from Aldes products through an AldesConnect box.

**Warning:** This integration is barely usable, given AldesConnect deep connectivity issues, even with the official mobile app (see the PlayStore comments for instance). Also, the API lacks several important features which makes this integration a lesser one.

## Supported products

### T.One® AIR

#### Implemented

+ Binary sensor entity to check if the product is connected to Aldes cloud
+ Temperature sensor entities for each room
+ Climate entities for each room that allow to set the target temperature

#### To do

+ Air cooling mode is not implemented yet since I still need to activate the feature

### Other products

I can't develop support for other products since I don't have them. But you can always submit a PR!

## Installation

This integration is available through HACS.

The username and password asked during the configuration are the same that you use for the Aldes mobile app.

## Development

This integration is based on https://github.com/custom-components/integration_blueprint
