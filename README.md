<h1 align="center">Anti Sleep Alarm For Drivers</h1>
 
 The Alcohol Detection System with Wireless Communication utilizes two Arduino Nano boards and NRF24L01 modules to detect alcohol levels and monitor eye closure. The system consists of a transmitter and a receiver. The transmitter, connected to an eye sensor, continuously reads the eye sensor value and wirelessly transmits it to the receiver using the NRF24L01 module. The receiver, connected to a motor, buzzer, and alcohol sensor, receives the eye sensor value and alcohol sensor value.
Upon receiving the values, the receiver performs the following actions:

If the alcohol sensor value exceeds a predefined threshold, indicating alcohol presence, the motor is stopped, and the buzzer is activated to alert the user.If the eye sensor value indicates closed eyes, suggesting drowsiness or fatigue, the motor is stopped, and the buzzer is activated.If neither of the above conditions is met, indicating the absence of alcohol or closed eyes, the motor is started, and the buzzer is deactivated.The system operates wirelessly, enabling real-time monitoring of alcohol levels and eye closure without physical connections between the components. This design offers the potential for use in applications such as automotive safety systems or workplace safety monitoring.
