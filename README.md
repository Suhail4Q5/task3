# task3
*COMPANY NAME*:CODTECH IT SOLUTION 

*NAME*:SHAIK SUHAIL

*INTERN ID*:CT06DF2960

*DOMAIN*:EMBEDDED SYSTEM

*DURATION*:6 WEEKS

*MENTOR*:NEELA SANTHOSH

*DESCRIPTION*:Temperature Monitoring System Description
A Temperature Monitoring System is an electronic setup designed to measure and display the temperature in real-time. Using a temperature sensor like the LM35, DHT11, or DS18B20, the system collects analog or digital data and processes it with a microcontroller (e.g., Arduino). The processed data is then displayed on an LCD or sent to a serial monitor for monitoring and analysis.
**Key Components:**
Temperature Sensor:
The LM35 sensor outputs an analog voltage proportional to the temperature.
The relationship is linear: 10mV corresponds to 1°C.
Microcontroller:
An Arduino processes the sensor's data using its ADC (Analog-to-Digital Converter).
It converts the analog signal into a readable temperature value in °C.
Display:
A 16x2 LCD displays the temperature for local monitoring.
The serial monitor (via USB and Arduino IDE) provides a secondary output for remote observation.
**How It Works:**
The sensor measures ambient temperature and generates a voltage.

The Arduino reads the sensor's output and converts it into a temperature using a formula.

The processed temperature is displayed on the LCD and printed to the serial monitor.

The system updates readings every second to ensure real-time monitoring.

**Applications:**
Home automation and climate control

Industrial temperature monitoring

Laboratory experiments and environmental studies

This system provides a simple, efficient, and cost-effective way to measure temperature, making it ideal for DIY projects and educational purposes.
