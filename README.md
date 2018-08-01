# AssimilateCrouton

The files are already rendered HTML/CSS from PUG/LESS.

NPM has not been used other than for a webserver (npm start from root).

I will fix NPM with an update to Polymer 3.

## Goals

~Color for each Device (considered by edfungus). Have piggy-backed endpointJson for now~.

Do not remove cards with LWT.

Heartbeat card - broken with LWT.

~Custom advanced editing cards (like scheduling) that add with flag from device info~

~CORS friendly webcomponents hosted from WiFi thing webserver~

~Show/hide cards from "Device card"~


## Hosting

You can test the dashboard locally on your DEV box:
- From the commandline in the root folder
- npm start <enter>
- the lite-server is spun up for http://localhost:10001

Deploy to a static webserver:
- copy all folders except node_modules
- copy index.html (and possibly web.config)


## Cards

### assim-weekview - 15 minute intervals

![Weekview Card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-weekview-1.png)

![Weekview Card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-weekview-1a.png)

### assim-weekview - 1 hour intervals

![Weekview Card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-weekview-2.png)

![Weekview Card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-weekview-2a.png)

### assim-weekview - 3 hour intervals

![Weekview Card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-weekview-3.png)

![Weekview Card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-weekview-3a.png)

### assim-device - show/hide cards, device details

![Device Card Default](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-device-1.png)

![Device Card Show/Hide list](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-device-2.png)

![Device Card Hide card](https://github.com/IOT-123/AssimilateCrouton/raw/master/images/assim-device-3.png)