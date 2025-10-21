log 6



This lab helped me understand how different parts of an IoT system work together. I set up a Mosquitto MQTT broker on the Raspberry Pi and used it to receive data from an ESP32 connected to a temperature sensor. At first, getting the ESP32 to connect to WiFi and send MQTT messages was tricky, especially making sure the sensor was wired and addressed correctly. But once I got the temperature data showing up on the Raspberry Pi using the paho.mqtt client, it felt really satisfying. I learned a lot about topics, bitwise operations, and the importance of matching configurations exactly. Seeing real-time data move from hardware to code made it all click for me. It felt like building a working system from scratch.
