# NodeRed-Weewx2Domoticz
NodeRed flow from Weewx to Domoticz

This (2) flows convert weewx mqtt messages to Domoticz mqtt messages.
This flows contains the needed MQTT broker (do not need to install separate MQTT broker)

Required :
* Weewx (www.weewx.com)
* Weewx MQTT extension (https://github.com/weewx/weewx/wiki/mqtt).

* Domoticz (www.domoticz.com)

* Node-Red (https://nodered.org/)
* node-red-contrib-aedes  (MQTT Broker nodered, install it with the command: cd ~/.node-red && npm install node-red-contrib-aedes ) 

Use the node-red web interface to import this json file. Then edit each sensor node to set your Domoticz Sensor IDX.




