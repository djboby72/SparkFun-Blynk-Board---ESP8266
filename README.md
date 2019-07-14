# SparkFun-Blynk-Board---ESP8266
Add support for SparkFun Blynk Board - ESP8266 in Arduino.

The file is used to add support in Arduino for the SparkFun Blynk Board - ESP8266.
Pay attention to the removal of generic support esp8266 if it is already installed because it is incompatible with Sparkfun BlynkBoard.

The original file was downloaded from
https://raw.githubusercontent.com/sparkfun/Arduino_Boards/master/IDE_Board_Manager/package_sparkfun_index.json
It was updated by replacing the path
http://arduino.esp8266.com/
with
https://github.com/esp8266/Arduino/releases/download/2.3.0/
to support the instalation of SparkFun Blynk Board - ESP8266 in Arduino when arduino.esp8266.com server is down.
