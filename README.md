
This project represents a prototype of an autonomous maze-solving robot designed to navigate through complex paths and avoid obstacles. The robot uses sensors to detect walls and make real-time decisions while moving.
The goal of this project is to simulate how intelligent robotic systems can autonomously explore unknown environments and find optimal paths.

Project Objective
The objective of this project is to design and improve a maze-solving robot that can move efficiently داخل المتاهة بدون تدخل بشري. The project focuses on enhancing obstacle detection, decision-making algorithms, and movement control to achieve faster and more accurate navigation.

System Description

The system consists of a mobile robotic car equipped with multiple distance sensors and a control unit. The robot continuously scans its surroundings (front, left, and right) to detect obstacles and decide the best direction to move.
It uses motors to navigate and can adjust its path dynamically based on sensor readings.

Main Components

Chassis (robot car body)
Two DC motors (with or without encoders)
Motor driver module (e.g., L298N)
Ultrasonic sensors (front, right, left)
Servo motor (for scanning movement)
Microcontroller (ESP32 or Arduino)
Power supply (batteries)
Optional: Flame sensor & buzzer (for extra features)

How the System Works

The robot starts moving forward inside the maze.
Ultrasonic sensors continuously measure distances from obstacles.
If the path ahead is clear, the robot keeps moving forward.
If an obstacle is detected, the robot compares left and right distances.
The robot chooses the direction with more free space.
If no clear path is available, the robot moves backward and retries.
The process repeats until the robot exits the maze.


## Team members
- Ahmed Mohamed Nail
- John George Abdelmseih
- Mohamed Mosad Elbana
- Omar Abdelkarim Elrifay
