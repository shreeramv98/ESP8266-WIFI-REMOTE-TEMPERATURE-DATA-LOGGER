# ESP8266-WIFI-REMOTE-TEMPERATURE-DATA-LOGGER-

OBJECTIVE:

To obtain the plot and monitor real time temperature values of any remote location.

ABSTRACT:

The project is based on logging the data of temperature readings in a remote location. It is widely used in a lot of IOT applications.
The project makes use of WiFi to transmit and receive the data from the sensor placed in a remote location.

The WiFi module used in this module is ESP8266-12 NodeMCU. This is a WiFi module has 12 GPIO pins and the firmware runs of the ESP8266 SOC. The NodeMCU refers the name of the firmware used and it is built in the programming language Lua. We make use of the temperature sensor LM35 to obtain the analog readings. We also use MQTT (machine-to-machine (M2M)/"Internet of Things" connectivity protocol) broker which is a lightweight publishing/subscribe messaging transport. The data is transmitted using WiFi to the webserver. The readings are also visualized in the THIS PEAK graph platform for better results.

HARDWARE REQUIREMENT/DESCRIPTION:

ESP8266-12 Node MCU, LM35 Temperature Sensor, Jumper Wires, USB Cable

COMPONENT SPECIFICATIONS:

ESP8266 Module pins are used for TX, RX of data, I/O ports to the LM35 Temperature Sensor
