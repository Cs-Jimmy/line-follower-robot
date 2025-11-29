# Line Follower Robot Car
This Arduino-powered line follower robot is designed to:

- Detect and follow a black line on a white surface using an array of 6 infrared (IR) sensors.

- Adjust its direction dynamically to the left or right based on sensor input to stay on track.

- Stop safely when the line is lost or not detected by any of the sensors.

# How It Works
The robot continuously reads input from 6 IR sensors arranged from left to right. Based on which sensors detect the black line:

- If the middle sensors detect the line → it moves **forward**.

- If the left-side sensors detect the line → it turns **left**.

- If the right-side sensors detect the line → it turns **right**.

- If no sensors detect the line → it **stops** to prevent going off-track.

# Hardware Components
- Arduino Uno

- L298N Motor Driver

- 2× DC Motors

- 6× IR Sensors

- LM317 DC-DC Module

- Rechargeable Batteries


