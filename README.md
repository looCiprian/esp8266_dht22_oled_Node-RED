# Wemos D1 mini (esp8266) + dht22 + oled + Node-RED
A program to display temperature, humidity, heat temperature, temperature graph and humidity graph on the Oled Display. Furthermode, thanks to the WiFi module it is possible to send and receive information to and from mqtt server in order to display temperature, humidity, heat and control the relè using Node-RED web page.

## Hardware
1. Wemos d1 mini
2. Wemos shield DHT22
3. Wemos OLED shield (V2.0.0)
4. Relè

## Software
### Libraries
1. Adafruit_GFX.h
2. Adafruit_SSD1306.h
3. DHT.h
4. ESP8266WiFi.h
5. PubSubClient.h (Change the mqtt server ip in the main.ino code as for Node-RED/flows.json)
6. SPI.h
7. Wire.h
8. WiFiManager.h (For the first use connect to "Wemos-temperature" wifi and browse 192.168.4.1 in order to set your home ssid and password)

## Network diagram

![Network Diagram](https://github.com/looCiprian/esp8266_dht22_oled_Node-RED/blob/master/images/network.png)

## Preview
### Oled display

![Oled Display](https://github.com/looCiprian/esp8266_dht22_oled_Node-RED/blob/master/images/wemos_display.gif)

### Node-RED dashboard

![Home](https://github.com/looCiprian/esp8266_dht22_oled_Node-RED/blob/master/Node-RED/images/home.png)
![Charts](https://github.com/looCiprian/esp8266_dht22_oled_Node-RED/blob/master/Node-RED/images/charts.png)
![Control](https://github.com/looCiprian/esp8266_dht22_oled_Node-RED/blob/master/Node-RED/images/control.png)

