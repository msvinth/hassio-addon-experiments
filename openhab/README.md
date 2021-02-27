OpenHAB 2
---------

This currenly only works on amd64 architecture.
Tested on Intel NUC
# Building this locally takes 10 minutes on my Raspberry Pi 3. So when clicking install in the UI, it will timeout. Don't worry, after 10 minutes it will popup as installed and you can start it.

 - Based off https://github.com/openhab/openhab-docker/tree/master/2.10.0/amd64
 - Added `ENV VERSION %%VERSION%%` to satisfy Hass.io
 - Supports Ingress. May be cases where it does not work fully. openHab does not really support this, but PaperUI seems to work fine.
 - Created a config.json that optionally exposes port 8080 (on which OpenHAB exposes their HTTP server)
 - openHab conf folder is available in HomeAssistant config folder so that it can be easily edited with the Home Assistant VSCode addon.


![OpenHAB2 UI](./ui.png)
