# **Maze Solver Car - Obstacle-Avoidance System**
A robotics project designed to navigate through mazes and avoid obstacles autonomously using ultrasonic sensors and motor control. This system uses multiple sensors to detect obstacles and decide the optimal path for navigation in real-time.
---
## **Features**
- **Obstacle Avoidance**: Detects and avoids obstacles dynamically using three ultrasonic sensors.  
- **Autonomous Navigation**: Navigates through mazes or predefined tracks without human intervention.  
- **Real-Time Decision Making**: Implements logic to choose the optimal direction (left, right, or forward).  
- **Debugging Support**: Outputs sensor data to the Serial Monitor for easy troubleshooting.  
- **Flexible Thresholds**: Adjustable distance threshold for obstacle detection to suit various environments.  
---
## **Tech Stack**
- **Programming Language**: C++ (Arduino IDE)  
- **Hardware Components**:
  - Ultrasonic Sensors (HC-SR04)  
  - Motor Driver Module (L298N or similar)  
  - DC Motors  
  - Arduino Microcontroller  
---
## **Getting Started**
### **Prerequisites**
- **Hardware Setup**:  
  - Arduino-compatible microcontroller  
  - 3 ultrasonic sensors (front, left, right)  
  - Motor driver module  
  - 2 DC motors  
  - Power source  
- **Software Requirements**:  
  - Arduino IDE  
  - [NewPing Library](https://bitbucket.org/teckel12/arduino-new-ping/wiki/Home)  
### **Installation**
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/maze-solver-car.git
## Installation
1. Open the Arduino IDE.
2. Go to `Sketch > Include Library > Manage Libraries`.
3. Search for **NewPing** and click **Install**.
## Upload the Code
1. Connect your Arduino to your computer.
2. Open the `maze-solver.ino` file in the Arduino IDE.
3. Select the correct **Board** and **Port** under the **Tools** menu.
4. Click **Upload**.
## How It Works
### Obstacle Detection
- Ultrasonic sensors measure distances to obstacles in the front, left, and right directions.
### Decision Making
- If an obstacle is detected in front, the robot stops, moves backward, and chooses a new direction.
- It turns left or right based on the available space.
### Movement
- Motor control pins enable forward, backward, and turning motions.
## Future Enhancements
- **Advanced Algorithms:** Implement A* or other pathfinding algorithms for more efficient maze solving.
- **Camera Integration:** Add computer vision capabilities for visual obstacle detection.
- **IoT Connectivity:** Enable remote monitoring and control via IoT platforms.
- **Battery Optimization:** Enhance power management for longer operation times.
## Contributing
Contributions are welcome! To contribute, follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
# Project Title
## Commit and Push Changes
- Commit your changes and push to your fork.
- Create a pull request for review.
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
## Contact
For any queries or suggestions, feel free to reach out:
- **Email:** [parasspatil10@gmail.com](mailto:parasspatil10@gmail.com)
- **GitHub:** [(https://github.com/paraspatil21)]((https://github.com/paraspatil21))
- **GitHub:** [https://github.com/paraspatil21]((https://github.com/paraspatil21))
### How to Use:
- Replace `your.email@example.com` and `https://github.com/yourusername` with your actual contact details.
- Save this as `README.md` in your project folder to display it on GitHub. 
Let me know if you’d like further customizations!
