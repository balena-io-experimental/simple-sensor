# simple-sensor
Read a sensor connected to your device and send the readings to another device via MQTT. Works great with balenaSense 2 and Home Assistant.

##Use
Add a device variable `MQTT_ADDRESS` with the IP of the broker or device you wish to send the sensor data to.

This project uses the [sensor block](https://github.com/balenablocks/sensor) so you can utilize any of the device variables listed in that repo.
