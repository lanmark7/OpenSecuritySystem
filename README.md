# OpenSecuritySystem
A lot of houses either have an existing wired security system or are prewired for one.  Alarm systems in general have been quite out of date and so the hope for this project is to leverage a prewired security system and bring it up to speed with newer technologies like MQTT and other smart home capabilities.  Ring and other companies have modern systems but almost all of them require internet connectivity and paid cloud services.

## Equipment

### Main Controller
* Arduino Mega 2560 controller
* Wired / Wifi module
* MQTT messaging 
* LoRa transceiver

### Remote Sensors
* LoRa transceiver
* DHT22 temp/humidity sensor
* Motion sensor
* Ultrasonic distance sensor
* Ambient light sensor
* Push button for event triggering (i.e. garage door)
