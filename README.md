*IoT Based Air Quality Index Monitoring System – Monitor PM2.5, PM10, and CO using ESP32*

As winter sets in, the air hanging over us thickens with smoke and gaseous emissions from burning fields, industrial factories, and vehicular traffic, blocking out the sun and making it hard to breathe. Experts say that the high levels of air pollution and COVID-19 pandemic can be a dangerous mix that can have serious consequences. The necessity for real-time monitoring of Air Quality is very glaring.

So in this project, we are going to build an ESP32 Air Quality Monitoring System using Nova PM SDS011 sensor, MQ-7 sensor, and DHT11 sensor. We will also be using an OLED Display module to display Air Quality Values. The Air Quality Index (AQI) in India is based on eight pollutants, PM10, PM2.5, SO2 and NO2, CO, Ozone, NH3, and Pb. However, it is not necessary to measure all of the pollutants. So we are going to measure the concentration of PM2.5, PM10, and Carbon Monoxide to calculate the Air Quality Index. The AQI values will be published on Adafruit IO so that we can monitor it from anywhere. Previously we have also measured the concentration of LPG, Smoke, and Ammonia gas using Arduino.

*Components Required:*

ESP32

Nova PM Sensor SDS011

0.96’ SPI OLED Display Module

DHT11 Sensor

MQ-7 Sensor

Jumper Wires
