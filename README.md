# robox--robotic-car
Robox: Arduino-based Bluetooth robot with motors, ultrasonic sensor, and servo. Ideal for surveillance, automation, and remote inspection. Control via mobile app.

![image](https://github.com/biswadeep-roy/robox--robotic-car/assets/74821633/43046c9b-d9ac-42d0-aec5-8fdabd52355d)


**Overview**

Robox is a small robotic car project built using Arduino, designed to be controlled via Bluetooth using an HC-05 module. The robot is equipped with two motors for movement, an ultrasonic sensor for obstacle detection, and a servo motor to move a sensor arm horizontally. This versatile robot has various applications, including surveillance, home automation, agricultural automation, remote inspection, and environmental monitoring.

**Features**

Motor Control: Two motors are controlled by motor drivers, allowing the robot to move forward, backward, turn left, turn right, or stop.

Bluetooth Communication: An HC-05 module enables Bluetooth communication, allowing control of the robot from a smartphone or other Bluetooth-enabled devices.

Ultrasonic Sensor: The ultrasonic sensor detects obstacles in front of the robot by emitting high-frequency sound waves and measuring the time it takes for them to return.

Servo Motor: A servo motor moves a sensor arm horizontally, aiding in obstacle avoidance and path clearing.

Obstacle Detection: When an obstacle is detected within 20 cm by the ultrasonic sensors, the robot stops moving, and the servo motor clears the obstruction before resuming its course.

Power Supply: The robot is powered by a battery or an external power source, supplying power to its microprocessor, motors, Bluetooth module, ultrasonic sensors, and servo motor.



**Applications**

Robox can be used in various scenarios, including:

Surveillance: Use the robot to monitor areas and capture photos or videos, transmitting them to your phone. The servo motor can help cover a larger area.

Home Automation: Automate tasks like turning lights on/off, opening/closing doors, and moving objects based on user-defined schedules or triggers.

Agricultural Automation: Employ the robot for tasks like planting, watering, and harvesting crops, with remote control or autonomous operation.

Remote Inspection: Conduct inspections in hard-to-reach or hazardous areas, receiving live video and sensor data on your phone.

Environmental Monitoring: Monitor temperature, humidity, and air quality in specific areas, with data transmitted to your phone via Bluetooth.

**Hardware Setup**

Arduino Uno: Set up the Arduino Uno board for programming and control.

Motors: Connect the two motors to pins 2-5 for motor control.

Ultrasonic Sensor: Wire the ultrasonic sensor to pins 6 (trigger) and 7 (echo) for obstacle detection.

Bluetooth Module: Connect the HC-05 module's RXD pin to Arduino pin 1 and TXD to pin 0 for Bluetooth communication.

Servo Motor: Wire the servo motor's data pin to A0 for horizontal movement.

Power Supply: Power the robot's components, including the Arduino, using a suitable battery or external power source.

**Code**

The Arduino code provided in this repository allows you to control the robot's movements via Bluetooth. The robot will stop automatically if it detects an obstacle within 20 cm and will resume moving once the obstacle is cleared.

**Getting Started**

Compile and upload the provided code to the Arduino.

Power up the robot.

Use your mobile device to connect to the robot via Bluetooth.

Control the robot's movements using the provided controller APK.

Up Arrow: Move forward
Side Arrows: Move left or right
Down Arrow: Move backward

**Additional Resources**

Video Demo: Watch the demonstration video in this repository to see Robox in action.

Presentation: Refer to the included PowerPoint presentation for a detailed overview of the project.
 
**License**
This project is licensed under the [MIT] License - see the LICENSE.md file for details.
