#Wokwi-Design-Code

{
  "version": 1,
  "author": "YASHOVERDHAN_SINGH",
  "editor": "wokwi",
  "parts": [
    { "type": "board-esp32-devkit-c-v4", "id": "esp", "top": 38.4, "left": 139.24, "attrs": {} },
    {
      "type": "board-ssd1306",
      "id": "oled1",
      "top": 233.54,
      "left": -47.77,
      "attrs": { "i2cAddress": "0x3c" }
    },
    { "type": "wokwi-servo", "id": "servo1", "top": 94, "left": 307.2, "attrs": {} },
    { "type": "wokwi-dht22", "id": "dht1", "top": -66.9, "left": 292.2, "attrs": {} },
    { "type": "wokwi-potentiometer", "id": "pot1", "top": -58.9, "left": -0.2, "attrs": {} },
    { "type": "wokwi-potentiometer", "id": "pot2", "top": 219.5, "left": 345.4, "attrs": {} },
    { "type": "wokwi-potentiometer", "id": "pot3", "top": -58.9, "left": 143.8, "attrs": {} }
  ],
  "connections": [
    [ "esp:TX", "$serialMonitor:RX", "", [] ],
    [ "esp:RX", "$serialMonitor:TX", "", [] ],
    [ "pot1:SIG", "esp:VP", "green", [ "v38.4", "h95.6", "v38.4" ] ],
    [ "pot1:VCC", "esp:3V3", "red", [ "v19.2", "h85.6" ] ],
    [ "pot1:GND", "esp:GND.1", "black", [ "v48", "h96", "v134.4" ] ],
    [ "pot3:SIG", "esp:VN", "green", [ "v9.6", "h-77.2", "v76.8" ] ],
    [ "pot3:VCC", "esp:3V3", "red", [ "v28.8", "h-68" ] ],
    [ "pot3:GND", "esp:GND.1", "black", [ "v0", "h-48", "v182.4" ] ],
    [ "pot2:SIG", "esp:34", "green", [ "v9.6", "h-269.2", "v-134.4", "h0", "v-57.6" ] ],
    [ "pot2:VCC", "esp:3V3", "red", [ "v19.2", "h-298.4", "v-240" ] ],
    [ "pot2:GND", "esp:GND.1", "black", [ "v48", "h-249.6", "v-144", "h19.2" ] ],
    [ "esp:18", "servo1:PWM", "green", [ "h9.6", "v19.2" ] ],
    [ "servo1:V+", "esp:3V3", "green", [ "h-48", "v-115.1", "h-163.2", "v28.8" ] ],
    [ "dht1:VCC", "esp:3V3", "red", [ "v-19.2", "h-163.2" ] ],
    [ "dht1:SDA", "esp:4", "green", [ "v9.6", "h-47.9", "v124.8" ] ],
    [ "oled1:GND", "esp:GND.1", "black", [ "v0" ] ],
    [ "servo1:GND", "esp:GND.1", "black", [ "h-57.6", "v124.8", "h-115.2", "v-76.8" ] ],
    [ "dht1:GND", "esp:GND.1", "black", [ "v48", "h-86.4", "v172.8", "h-115.2", "v-76.8" ] ],
    [ "oled1:SDA", "esp:21", "green", [ "v-19.2", "h57.67", "v67.2", "h211.2", "v-172.8" ] ],
    [ "oled1:SCL", "esp:22", "green", [ "v-9.6", "h57.9", "v48", "h211.2", "v-9.6" ] ],
    [ "oled1:VCC", "esp:3V3", "red", [ "v-38.4", "h96.15", "v-134.4" ] ]
  ],
  "dependencies": {}
}
