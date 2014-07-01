# CueMote
CueMote is a simple web based remote control for the [CueServer](http://interactive-online.com/products/cueserver/overview) by Interactive Technologies.

CueMote provides a responsive remote for use within any browser.  Desktop browsers may also use keybindings to control the CueServer.

Customize this small application for your installation.

## Installation Notes
* Download and unpack CueMote.  All control is done clientside so CueMote can be served by just about any webserver.

* This project utilizes `cueserver.js` provided by Interactive Technologies.  This small javascript library should be [downloaded](http://interactive-online.com/products/cueserver/downloads) and placed within the `js` folder.


* Within the index.html file, change  `gIPAddress` to match the IP address of the cueserver.
```
var gIPAddress = '192.168.223.35';
```

* The startup image and icon may be customized to fit your installation needs.


