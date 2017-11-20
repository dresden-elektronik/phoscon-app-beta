# Phoscon App Beta


#### Discussion

Please use the public GitHub issues to discuss, report and request anything related to the beta app.

https://github.com/dresden-elektronik/deconz-rest-plugin/issues


## Requirements
* phone, tablet or PC
* supported Browsers: Chrome, Firefox, Safari and Samsung Browser
* Raspberry Pi 2/3 or PC with Ubuntu/Windows
* RaspBee or ConBee with latest firmware
* most recent beta version of deCONZ, for install instructions (steps 1&ndash;3) refer to:

   https://github.com/dresden-elektronik/deconz-rest-plugin 
   
## Usage
To try the new app open the following link:

http://www.dresden-elektronik.de/pwa


This preliminary login page shows connected gateways. Initially the search may take a few minutes; the search can be repeated by clicking the Phoscon logo.

Select your your gateway and login with its password (default: delight).

#### Install on homescreen
On mobile devices the app can be "installed" on homescreen from the menu in Safari, Chrome or Samsung browser.

## Notes

* The app is still beta and has many missing or not completed parts.
* The app can be used beside the old web app.
* The app is loaded from our web server but *runs just locally* in your browser and *communicates directly* with the gateway (no cloud).
* Our server doesn't have any access to your local network nor gateway.
* The app works offline once loaded for the first time (via HTML5 AppCache).
* The app is served via HTTP instead of HTTPS for various technical reasons. We plan to switch to HTTPS after WebRTC will be available in all major browsers.

#### Update 20 Nov 2017

* mobile support for phone and tablet portrait mode has progressed a lot for various screens
* usability of navigation and sidemenu is more linear
* schedules is now available for tablet and PC
* scene editor uses manual saving now and won't just call the first scene on enter
* heaps of smaller bug fixes and improments
* with deCONZ 2.04.90 espeacially mobile devices will notice speed improvements when accessing the API (TCP_NODELAY)

## Work in progress

The following features are not available in public yet or currently worked on:

* ~~mobile phone and tablet portrait mode~~
* motion sensor control configuration is functional but only 50% of the UI is implemented
* Philips Hue Tap setup and configuration
* ~~IKEA TRADFRI setup wizards missing images~~
* ~~schedules~~
* IKEA Tradfri E27 CWS color bulb sliders moving back
* time ranges for motion sensor controls
* editor to connect arbitrary switch buttons to various actions, like calling a scene, disable sensors controls, etc.
* using the app with Firefox 57 on mobile is very slow for some unknown reason: under investigation


