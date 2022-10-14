# Streaming Live Data to ThingsBoard

This project involves setting up a MQTT protocol to produce temperature and humidity data.  This data is produced in the TBpublish.py file, which will use the Paho Python library to connect to the MQTT broker.  The data producted by the MQTT protocol is published to ThingsBoard.  I set up a Realtime database in Firebase that will store the temperatue and humidity data, as well as the alarms. 

- The TBpublish.py python script with Paho will be the client. 
  - This file publishes the temperature data to ThingsBoard
- ThingsBoard uses the rule chain to pass the data to Firebase
  - # TODO: Add more details


### Technologies used
- Mosquitto
- ThingsBoard
- Firebase



