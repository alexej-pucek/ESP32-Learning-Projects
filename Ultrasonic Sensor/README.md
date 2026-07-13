**ULTRASONIC DISTANCE SENSOR**

In this project I used the HC-SR04 Ultrasonic Sensor to read the distance in front of it, and print them to the Serial Monitor.
I also learned how to make a Voltage Divider. It was needed, because the Echo Pin on the sensor outputs 5V, and my ESP32 only supports 3.3V. 
It would also work with the 5V, but that can cause some long term damage to the pin. This sensor isn´t very reliable after 50cm in distance, because the ultrasonic waves
spread a lot to the environment, and that causes false data. This can be overcomed using some sort of Median Filter, but I´m not that advanced to do that, at the moment.

TIME: 30 min + 10 min learning how to make voltage divider.

DIFFICULTY: 7/10.

LEARNING VALUE: 8/10.

DATE: 13.7.2026.
