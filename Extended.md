# Add Sensor data sensing feature
This extension is to add feature that collect data from SenseHat sensors and send collected data to Azure IoT Hub 
## Extension
Add Sensehat-Sense module and modified deployment.template.json. 
SenseHat-Sense module access to Sense Hat sensors, collect measured data and send to edgeHub message bus.

## How to use
You can run this modules on Azure IoT Edge runtime by just the way described in [README.md](./README.md). 
But build is spent very long time ;-)

## Reference
I refere [Raspberry PI+SenseHat sample in hackster](https://www.hackster.io/ngkurt/azure-iot-edge-with-sense-hat-and-raspberry-pi-06791b) to create SenseHat-Sense module. Thank [Gökhan Kurt](https://www.hackster.io/ngkurt)!
