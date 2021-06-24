# simple-sensor
Read a sensor connected to your device and send the readings to another device via MQTT. Works great with [balenaSense 2](https://github.com/balenalabs/balena-sense) and Home Assistant. This project uses the [sensor block](https://github.com/balenablocks/sensor) so check out that repository for the list of supported sensors and options.

[![balena deploy button](https://www.balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/balena-io-playground/simple-sensor)

## Use
Add a device variable `MQTT_ADDRESS` with the IP address of the broker or device you wish to send the sensor data to. If using with balenaSense 2, set this variable to the internal IP address of your balenaSense2 device.


