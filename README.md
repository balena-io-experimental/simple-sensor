# simple-sensor
Read a sensor connected to your device and send the readings to another device via MQTT. Works great with balenaSense 2 and Home Assistant.

[![balena deploy button](https://www.balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/balena-io-playground/simple-sensor)

## Use
Add a device variable `MQTT_ADDRESS` with the IP address of the broker or device you wish to send the sensor data to.

This project uses the [sensor block](https://github.com/balenablocks/sensor) so you can utilize any of the device variables listed in that repo.
