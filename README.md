# Obstacle-Avoider-Robot
An Arduino-based mobile robot that detects obstacles using an ultrasonic distance sensor and adjusts its movement to avoid collisions. This project explores the fundamentals of robotics, embedded systems, sensor integration, and motor control.

📌 Project Overview

The robot uses an ultrasonic sensor to measure the distance between itself and nearby objects. Based on the measured distance, the Arduino processes the sensor readings and controls the motors to change the robot's direction when an obstacle is detected.

This project demonstrates the integration of hardware and software to build a basic autonomous mobile robot.

🎯 Objectives

Build a mobile robot capable of detecting nearby obstacles.

Integrate ultrasonic sensing with a microcontroller.

Control DC motors using a motor driver.

Implement basic decision-making for autonomous movement.

Understand the fundamentals of sensor-based robotic navigation.

🛠️ Hardware Components

Component

Purpose

Arduino Uno-                                        Reads sensor data and controls the robot

HC-SR04 ultrasonic sensor-                         Measures distance to obstacles

L298N motor driver-                                  Controls motor direction and movement

DC geared motors-                                    Drive the robot's wheels

Robot chassis and wheels-                            Provide the mechanical structure

Battery/power supply -                               Powers the robot electronics and motors

Jumper wires-                                        Connect the electronic components

⚙️ Working Principle

Distance measurement: The ultrasonic sensor emits sound pulses and measures the returning echo.

Signal processing: The Arduino calculates the approximate distance to the detected obstacle.

Decision-making: The program compares the measured distance with a predefined threshold.

Motor control: The motor driver receives control signals from the Arduino to move or turn the robot.

Obstacle avoidance: The robot changes direction when an obstacle is detected and resumes movement according to the programmed logic.

💻 Software and Tools

Programming language: Arduino C/C++

Microcontroller platform: Arduino Uno

Development environment: Arduino IDE

Concepts: Conditional logic, sensor interfacing, digital I/O, and motor control

👩‍💻 Author

Aafia Shamsi

Mechanical Engineering Undergraduate

Zakir Husain College of Engineering and Technology, Aligarh Muslim University
