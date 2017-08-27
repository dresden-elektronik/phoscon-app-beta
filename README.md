# Phoscon App Beta


#### Discussion

Please use the public GitHub issues of the to discuss, report and request anything related to the beta app.

https://github.com/dresden-elektronik/deconz-rest-plugin/issues


## Requirements
* tablet in landscape mode or PC (mobile phone and tablet portrait mode in progress)
* supported Browsers: Chrome, Firefox, Safari and Samsung Browser
* Raspberry Pi 2/3 or PC with Ubuntu
* RaspBee or ConBee with latest firmware
* recent beta version of deCONZ, for install instructions refer to:

   https://github.com/dresden-elektronik/deconz-rest-plugin 
   
## Usage
To try the new app open the following link:

http://www.dresden-elektronik.de/pwa


This preliminary login page shows connectes gateways. Initially the search may take a few minutes.

Select your your gateway and login with its password (default: delight).

**Note** By clicking on the Phoscon logo the search can be repeated.


## Notes

* The app is still beta and has many missing or not completed parts.
* The app can be used beside the old web app.
* The app is loaded from our web server but *runs just locally* in your browser and *communicates directly* with the gateway (no cloud).
* Our server doesn't have any access to your local network nor gateway.
* The app works offline once loaded for the first time (via HTML5 AppCache).
* The app is served via HTTP instead of HTTPS for various technical reasons. We plan to switch to HTTPS after WebRTC will be available in all major browsers.

## Work in progress

The following features are not available in public yet or currently worked on:

* motion sensor control configuration is functional but only 50% of the UI is implemented
* Philips Hue Tap setup and configuration
* IKEA TRADFRI setup wizards missing images
* schedules
