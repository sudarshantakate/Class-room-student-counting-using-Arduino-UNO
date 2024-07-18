# Class-room-student-counting-using-Arduino-UNO

This project is used in most colleges to count the number of students available in the classroom. Here, we haven't  used any ML algorithms. 

# Introduction 

This energy-efficient system uses InfraRed (IR) sensor pairs to count students entering or leaving a classroom, helping teachers take attendance. Here's how it works:
             IR sensor pairs detect students entering or leaving the classroom.
             The microcontroller (Arduino-UNO) processes the input and increments/decrements a counter accordingly.
             The count is displayed on a 7-segment display for arrivals and a 16x2 display for total attendance.
             
# Project Overview

This system is designed to optimize energy usage by counting the number of students entering and leaving a classroom. It uses InfraRed (IR) sensor pairs to detect movement. Each pair consists of two sensors placed at a distance from one another in opposite directions. When a person passes through the sensor area, the IR transmitter sends a signal to the receiver, which then sends the information to an Arduino UNO.

The microcontroller processes this input, increments a counter for each person entering, and displays the count on a 7-segment display. This feature aids teachers in taking attendance. Similarly, when a person exits, the system decrements the count. The updated count is displayed on a 16x2 display. This efficient system helps in energy conservation while providing real-time data on the number of people present in the classroom.
