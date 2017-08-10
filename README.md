# WeMOS-Beginners
Baby Steps for new users of the Arduino Platform and Wemos D1 Mini

Step 1: Read the documentation
[Read Documentation](https://wiki.wemos.cc/products:d1:d1_mini_pro)

Step 2: Download Arduino IDE:
[Mac](https://www.arduino.cc/en/Guide/MacOSX)
[Windows](https://www.arduino.cc/en/Guide/Windows)

Step 3: Download USB Driver
[Download Driver](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

Step 4: Install the ESP8266 board
[Instructions here!](https://github.com/esp8266/Arduino)
- Start Arduino and open Preferences window.
- Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field. You can add multiple URLs, separating them with commas.
- Open Boards Manager from Tools > Board menu and install esp8266 platform (and don't forget to select your ESP8266 board from Tools > Board menu after installation).

## Installing git
* [Git for Mac](https://github.com/blog/1510-installing-git-from-github-for-mac)
* [Git for Windows](https://git-scm.com/download/win)

## Custom Libraries
* [PubSubClient](https://github.com/knolleary/pubsubclient) (IOT Projects)
* Optional: ["128x64" OLED Screen SSD1306](https://github.com/squix78/esp8266-oled-ssd1306) or [Println](https://github.com/stevenvo/arduino-libraries)

## Cloud
* [CloudMQTT](https://customer.cloudmqtt.com/login)
1. Sign up for an account - with Cute-Cat (Free!)
2. Create an instance - name it anything you like
3. Create a user - I used "admin" with no password
4. Create a topic - Name it by your intended function, e.g. GPS_Lookup

## Mobile App
* For Android Users
1. Go to Google Play Store and download "[IoT MQTT Dashboard](https://play.google.com/store/apps/details?id=com.thn.iotmqttdashboard&hl=en)"
2. Create a connection with Client ID: {any}, Server, Port, Username, Password {Check Cloud MQTT}
3. Subscribe or Publish

## (For Contributors)
* [README Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
