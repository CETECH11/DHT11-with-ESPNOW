# DHT11-with-ESPNOW

![alt text](https://hackster.imgix.net/uploads/attachments/1607111/image_WVhGyCQla5.png?auto=compress%2Cformat&w=740&h=555&fit=max)

ESP-NOW is a wireless communication protocol based on the data-link layer that enables the direct, quick, and low-power control of smart devices without the need for a router. Espressif defines it and can work with Wi-Fi and Bluetooth LE. ESP-NOW provides flexible and low-power data transmission to all interconnected devices. It can also be used as an independent protocol that helps with device provisioning, debugging, and firmware upgrades.

ESP-NOW is a connectionless communication protocol developed by Espressif that features short packet transmission. This protocol enables multiple devices to talk to each other in an easy way. It is a fast communication protocol that can be used to exchange small messages (up to 250 bytes) between ESP32 or ESP8266 boards. ESP-NOW supports the following features: Encrypted and unencrypted unicast communication; Mixed encrypted and unencrypted peer devices; Up to 250-byte payload can be carried; Sending callback function that can be set to inform the application layer of transmission success or failure.

![alt text](https://hackster.imgix.net/uploads/attachments/1607112/image_S29vukB68f.png?auto=compress%2Cformat&w=740&h=555&fit=max)

ESP-NOW is a wireless communication protocol that is different from Wi-Fi and Bluetooth in that it reduces the five layers of the OSI model to only one1. Additionally, ESP-NOW occupies fewer CPU and flash resources than traditional connection protocols while co-exists with Wi-Fi and Bluetooth LE.

Bluetooth is used to connect short-range devices for sharing information, while Wi-Fi is used for providing high-speed internet access2. Wi-Fi provides high bandwidth because the speed of the internet is an important issue.

Max Distance:
The range of ESP-NOW is up to 480 meters when using the ESP-NOW protocol for bridging between multiple ESP32s1. The range can be further increased by enabling long-range ESP-NOW. When enabled, the PHY rate of ESP32 will be 512Kbps or 256Kbps.

Maximum nodes:
ESP-NOW supports various series of Espressif chips, providing a flexible data transmission that is suitable for connecting “one-to-many” and “many-to-many” devices.

Applications:
ESP-NOW is widely used in

--> smart-home appliances,
--> remote controlling,
--> sensors, etc.
In this tutorial, will see how to implement a basic ESP NOW communication between ESP32 Microcontrollers.

![alt text](https://components101.com/sites/default/files/components/DHT11-Sensor.jpg)

The DHT11 is a commonly used Temperature and humidity sensor that comes with a dedicated NTC to measure temperature and an 8-bit microcontroller to output the values of temperature and humidity as serial data.
The DHT11 is a commonly used Temperature and humidity sensor. The sensor comes with a dedicated NTC to measure temperature and an 8-bit microcontroller to output the values of temperature and humidity as serial data. The sensor is also factory calibrated and hence easy to interface with other microcontrollers.

The sensor can measure temperature from 0°C to 50°C and humidity from 20% to 90% with an accuracy of ±1°C and ±1%. So if you are looking to measure in this range then this sensor might be the right choice for you.
The DHT11 sensor can either be purchased as a sensor or as a module. Either way, the performance of the sensor is same. The sensor will come as a 4-pin package out of which only three pins will be used whereas the module will come with three pins as shown above.

The only difference between the sensor and module is that the module will have a filtering capacitor and pull-up resistor inbuilt, and for the sensor, you have to use them externally if required.


![alt text](https://hackster.imgix.net/uploads/attachments/1518136/8_tJuwoRM3dI.JPG?auto=compress%2Cformat&w=740&h=555&fit=max)

You must check out [PCBWAY](https://www.pcbway.com/) for ordering PCBs online for cheap!

You get 10 good-quality PCBs manufactured and shipped to your doorstep for cheap. You will also get a discount on shipping on your first order. Upload your Gerber files onto PCBWAY to get them manufactured with good quality and quick turnaround time. [PCBWay](https://www.pcbway.com/) now could provide a complete product solution, from design to enclosure production. Check out their online Gerber viewer function. With reward points, you can get free stuff from their gift shop.
