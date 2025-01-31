# Interactive LED Control using Python & Arduino 💡🤖

## Overview
This project utilizes **OpenCV** and **CVZone** in **Python** to detect hand gestures via a webcam, sending commands to an **Arduino**. The Arduino controls LEDs based on the number of fingers visible, enabling **real-time, interactive LED control** through **computer vision** and **serial communication**.

## Features ✨
- **Hand Gesture Recognition using OpenCV & CVZone** 🖐️
- **Real-Time Finger Detection & Counting** 🔢
- **Serial Communication with Arduino** 🔄
- **Dynamic LED Control Based on Finger Count** 💡
- **Live Visualization of Hand Gestures** 📹

## Project Structure 📂
```
📁 LED-Control-Using-OpenCV-Arduino
│── ide.m.ino        # Arduino code for LED control
│── main.py         # Python script for gesture detection & communication
│── LED control live demo.mp4  # Demonstration video
│── README.md       # Project Documentation
```

## Hardware Requirements 🛠️
- **Arduino UNO**
- **LEDs**
- **Resistors**
- **Jumper Wires**
- **USB Cable for Arduino**
- **Webcam**

## Installation & Setup ⚙️
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LED-Control-Using-OpenCV-Arduino.git
   ```
2. Install the required Python dependencies:
   ```bash
   pip install opencv-python cvzone mediapipe pyserial
   ```
3. Upload `ide.m.ino` to your **Arduino UNO** using the Arduino IDE.
4. Connect the hardware components as per the circuit diagram.
5. Run the Python script:
   ```bash
   python main.py
   ```

## Usage 🚀
1. **Start the Python script** to detect hand gestures.
2. **Hold your hand in front of the webcam** and raise fingers to control LEDs.
3. The **number of raised fingers** determines which LED(s) will turn on.
4. The program will continuously update the LED states in real time.
5. Press `ESC` (ASCII 27) to **exit the program** and close the video feed.

## Live Demo 🎥
![Live Demo](LED%20control%20live%20demo.mp4)

## Contributions 🤝
Feel free to **fork** the repository, **submit issues**, or **suggest improvements** for better real-time detection and control.

---
