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

   https://github.com/dresden-elektronik/deconz-rest-plugin#introduction
   
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

#### Update 10 Dec 2017

* new icons for Xiaomi sensors
* updated manuals for RaspBee and ConBee
* smaller bug fixes in schedules and manage lights pages
* a copy of the Phoscon App is now included in deCONZ package (since version 2.04.97)
* to open it use the `Phoscon App` button in deCONZ or navigate to `http://<ip-address>:<port>/pwa`
* the former WebApp lives next to it at `http://<ip-address>:<port>`

#### Update 4 Dec 2017

* Phoscon App Beta goes public

#### Update 3 Dec 2017

**Sensor control**
* motion sensor transitions are visualized in a diagram now
* improved transition list to be less cryptic; show action, dimm value and state times
* next on the list:
    + better ui to configure interaction between switches, motion- and contact sensors
    + support calling scenes as transition

* fix issue when renaming a group with a single light will actually rename the light
* small improvements in schedules editor
* fix some Firefox related ui issues


#### Update 30 Nov 2017

* fix various issues in scene editor for groups and switches
* discard changes in scene editor works reliable now
* add +/- buttons to manage lights page to change group membership faster (drag&drop works beside that too)
* add manual saving of group membership changes in manage lights page
* new Philips Hue motion sensor setup wizard (wip)
* fix bugs in schedules page
* faster discover gateway site
* improved `Help > Reset lights` wizard pages
* fix many smaller ui glitches

#### Update 20 Nov 2017

* mobile support for phone and tablet portrait mode has progressed a lot for various screens
* usability of navigation and sidemenu is more linear
* schedules is now available for tablet and PC
* scene editor uses manual saving now and won't just call the first scene on enter
* heaps of smaller bug fixes and improments
* with deCONZ 2.04.90 especially mobile devices will notice speed improvements when accessing the API (TCP_NODELAY)

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


