OpenHAB 2
---------

I have tested on Intel NUC.

Building this locally takes 10 minutes on Raspberry Pi 3. So when clicking install in the UI, it will timeout. Don't worry, after 10 minutes it will popup as installed and you can start it.

 - Supports Ingress. There may be cases where it does not work fully. openHab does not really support this as it expects to be hosted at the root url, but PaperUI seems to work fine.
 - Created a config.json that optionally exposes port 8080 (on which OpenHAB exposes their HTTP server). Use this if some scenario does not work with ingress.
 - openHab conf folder is available in HomeAssistant config folder so that it can be easily edited with the Home Assistant VSCode addon.


![OpenHAB2 UI](./ui.png)
