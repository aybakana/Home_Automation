# Home_Automation

## Project Overview
I set up a kind of Home Automation System with the help of an Arduino Nano, 2 nRF24L01+ wireless transceivers, a Rasperry Pi mini computer, a temperature sensor, and a humidity sensor.

The steps:

1- Arduino gets information from temperature and humidity sensors

2- Arduino sends information to the Rasperry Pi via nRF24L01 transceivers

3- Rasperry pi publishes the information to an MQTT channel

4- OpenHAB MQTT binding starts a web server and picks up the information and publish it
