#BlitZenz Sensor V0.1

##Arduino Sketch for a simple Atmospheric Sensor using an ESP32 NodeMCU module, a DHT11 Temp/Humidiy Sensor and an MQ135 Amospheric Gasses Sensor.  

###It connects to an MQTT server then:   
###- publishes "OK" to the topic "Start"   
###- subscribes to the topic "in", printing out any string messages it receives.   
###- Reads both sensors' outputs and publishes them through the "out" topic
