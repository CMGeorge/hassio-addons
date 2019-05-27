# Flashforge Finder API hass.io add-on
A hass.io add-on for exposing data from Flashforge Finder(s) as API endpoints for consumption as HA REST sensors. This project is more or less a wrapper around 01F0's work here: https://github.com/01F0/flashforge-finder-api.

## Usage
1) Install the addon and configure the port that the API will be served on. Default is 5000.

2) Start the addon. Information about your printer will be available at http://{homeassistant_ip}:{fff-api_port}/{printer_ip}/{info|head-location|temp|progress|status}

3) Configure RESTful sensors in HA as necessary
