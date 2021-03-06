**esp_mqtt_gen_purpose**
==========
Based on the [MQTT library for the ESP8266 ](https://github.com/tuanpmt/esp_mqtt) (thanks!)

**Features:**

Status of GPIO pins as published mqtt-message
Set status of arbitrary GPIO pin (on-off for now) via MQtt Message


**Authors:**
[Murf](https://murf.se)


**Hardware**
GPIO2 is connected to a NPN transistor. Base Collector Emmiter. GPIO2 to 1k resistor to Base of a NPN 3906 Transistor. Collector is conneted to Ground, Emittor is connected to the Relay. groound of relay to 5.0v (USB)
ESP8266 -03, GPIO 15 via 10k resistor to ground, CH_PD via 10k resistor to VCC 3.3v regulator AMS1117 connected to VCC5.0

**LICENSE - "MIT License"**

esp_mqtt_gen_purpose: Copyright (c) 2014-2015 Murf, https://murf.se
esp_mqtt: Copyright (c) 2014-2015 Tuan PM, https://twitter.com/TuanPMT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
