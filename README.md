# SIMPLE-LINE-FOLLOWER
A simple LEGO EV3 robot programmed using MicroPython to follow a line using a proportional control algorithm.

# LEGO EV3 Line Follower Robot 🚗🤖

This project demonstrates a simple line follower robot built using **LEGO MINDSTORMS EV3** and programmed with **MicroPython (Pybricks)**. The robot uses a **color sensor** to detect line deviation and corrects its path using a **proportional control algorithm**.

---

## 📦 Features

- Follows a black line on a white surface
- Proportional control for smooth and responsive turning
- Lightweight and easy to modify for custom tracks
- Built using EV3-G standard robot structure

---

## 🧠 How It Works

1. The EV3 Color Sensor reads the reflected light intensity.
2. It compares the value to a threshold (average of black and white).
3. Based on the deviation, the robot adjusts its turn rate proportionally.

