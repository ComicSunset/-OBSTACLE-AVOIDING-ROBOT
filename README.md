##  PathFinder-X: Intelligent Rover with Dynamic Obstacle Evasion and Bluetooth App Control

# ABSTRACT

"RoboRover AI" is a next-generation, semi-autonomous robotic system inspired by planetary rovers, capable of smart terrain navigation through real-time obstacle detection, distance measurement, and intelligent angle-based path correction. Designed using Arduino and controlled via a custom Android app developed in MIT App Inventor, the robot operates in two modes: manual and autonomous.
In autonomous mode, the rover uses an ultrasonic sensor to detect obstacles and calculate their distance. Based on this information and the estimated size of the obstacle, the system computes an optimal turning angle to navigate around it before resuming its path — mimicking decision-making strategies used in space exploration rovers. In manual mode, the user can steer the rover via Bluetooth using directional buttons in the mobile app.
Core components include an Arduino Uno, HC-SR04 ultrasonic sensor, L298N motor driver, DC motors, and a Bluetooth module (HC-05). The entire system is mounted on a durable chassis and powered by a rechargeable battery pack. The mobile app provides real-time control and mode switching, making the system interactive and easy to operate.
This project bridges embedded systems and real-time navigation logic to build a smart, cost-effective robotic solution ideal for educational use, obstacle-rich environments, or research prototypes in autonomous systems. The angle-based avoidance strategy sets it apart from traditional robots, offering a glimpse into intelligent robotics design inspired by real-world applications.

![image](https://github.com/user-attachments/assets/2ecca8f5-ce30-4278-8475-98a949e98b53)

# HARDWARE SETUP

![image](https://github.com/user-attachments/assets/acc8cd31-c4e8-4bef-9e2e-c33f590692c3)

# WORKING FLOW(SIMPLE DIAGRAM)

![image](https://github.com/user-attachments/assets/2c2e3fc9-8e97-47ad-972a-d1b0993ee54b)

# HARDWARE COMPNENETS USED 

1. Arduino Uno (or Nano)
What it is: A microcontroller board based on the ATmega328P.

Why it's used: It acts as the brain of the robot, processing inputs (like distance from the ultrasonic sensor) and controlling outputs (like motor movement). It runs the main logic for obstacle detection and movement control.

2. Ultrasonic Sensor (HC-SR04)
What it is: A distance-measuring sensor that uses sound waves to detect obstacles.

Why it's used: It detects obstacles in front of the robot by calculating the distance to them. Based on this data, the robot decides whether to move forward, turn, or stop.

3. L298N Motor Driver Module
What it is: A dual H-bridge motor driver that controls the speed and direction of DC motors.

Why it's used: The Arduino alone can’t provide enough current to run motors. The L298N safely controls motor direction and speed using PWM signals from the Arduino.

4. 2 DC Motors + Wheels
What they are: Small electric motors with attached wheels.

Why they're used: They provide locomotion to the robot, enabling it to move forward, backward, and turn based on control signals.

5. Chassis (Robot Frame)
What it is: The physical frame that holds all components together.

Why it's used: It provides mechanical structure and stability to the robot, ensuring all components are securely mounted and properly balanced.

6. Bluetooth Module (HC-05 / HC-06)
What it is: A wireless serial communication module using Bluetooth.

Why it's used: It allows the robot to be remotely controlled via a smartphone using a custom app made with MIT App Inventor. It receives commands like forward (F), backward (B), etc.

7. Battery Pack (Li-ion or 9V with holder)
What it is: A portable power supply.

Why it's used: It provides electrical power to the entire robot, including the Arduino, sensors, and motors. The choice depends on the desired runtime and current requirements.

8. Jump Wires / Breadboard (optional)
What they are: Electrical connecting tools.

Why they're used: To connect components without soldering and make the prototype easier to test and modify.





  



