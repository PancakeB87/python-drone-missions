# python-drone-missions

This project is part of my work with Drone Cadets. I helped create a Python-based mission planning algorithm for a DJI Tello Drone.
Drone communication occurs through Tello SDK and by sending UDP (User Datagram Protocol) Packets. In other words, a way to send messages to a Tello drone over Wifi.

In "main.py," a series of missions have been made, creating various shapes or simple maneuvers with the drone's movement. The following missions exist sequentially:
- Box Mission: Takeoff, create a horizontal square, land.
- Backflip Mission: Takeoff, do a backflip, land. 
- Door Mission: Takeoff, create a vertical door shape, land.
- Window Mission: Takeoff, create a vertical square window, land.
- Turning Door Mission: Takeoff, create a vertical door shape with intermediate yaw rotations, land.
- Turning Window Mission: Takeoff, create a vertical windown shape with intermediate yaw rotations, land.
- Coded Landing Mission: Takeoff, travels forward a user-inputted distance, land.
- Equilateral Triangle Mission: Takeoff, create a horizontal equilateral triangle, land.
- Star Mission: Takeoff, create a 5-point star, land.
- Turning Box Mission: Takeoff, create a horizontal square with intermediate yaw rotations, land.
- Loop Box Mission: Turning Box Mission in a for-loop.

This script is based off of "HelloDrone.ipynb," which is from a DroneBlocks Tello programming course.
