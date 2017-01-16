# Home-weather-monitor
A home weather monitoring system using Node-RED and IBM Watson IoT Platform in IBM Bluemix

## The model:
This project involves monitoring the temperature and humidity inside the home. 
For the hardware, the DHT22 sensor (the device) was connected to a Raspberry Pi (model: 3B), 
which was used as the gateway device. The Pi and the sensor are registered with the IBM Watson IoT Platform 
in Bluemix Cloud. Temperature, humidity data along with timestamps are sent from the Node-RED application 
on Pi to the Node-RED application in Bluemix. 

## Features:
* A simple webpage using Javascript and jQuery is created to display live data from the Cloud using websockets. 
* A dashboard to visual the incoming data fom the sensor, outdoor temperature and humidity from Openweathermap.
* Dashboard notification of live sensor data
* Indoor temperature and humidity monitoring with E-mail notifications.
* A MongoDB to persistently store historic data for future visualization purposes


## Contents:
This repository contains screenshots of the following:
* A picture of the hardware setup
* Screenshots of Node-RED flows in Raspberry Pi and Watson IoT Platform
* Text files containing JSON data for Node-RED flows in Raspberry Pi and IoT Platform
* A screenshot of the webpage and the dashboard.


