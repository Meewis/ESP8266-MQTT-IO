# ESP8266-MQTT-IO
My default ESP project with Wifi MQTT and IO

- automatic Wifi connection and reconnection (non blocking)
- DHCP network mode
- automatic MQTT broker connection  reconnection (non blocking)
- system class for time periodic puls and block signals
- button class for proper edge detection and pressed status of input signal
- MQTT periodic publish of 'live' counter, IP address and 'relais'status
- MQTT subscribe for 'relais' command
- IO for button, LED and relais
- Relais is toggled by pushing the button or a MQTT on or off command
