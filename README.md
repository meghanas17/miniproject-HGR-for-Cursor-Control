# Hand Gesture Controlled Cursor

This project allows users to control the computer mouse cursor using hand gestures detected in real-time via a webcam. It uses OpenCV for video capture and processing, MediaPipe for hand landmark detection, and PyAutoGUI for cursor control and click simulation. The project was developed using Python in PyCharm.

## Features

- Real-time hand tracking using MediaPipe
- Cursor movement based on index finger position
- Mouse click simulation when thumb and index finger pinch
- Compatible with both internal and external webcams

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- PyCharm (IDE)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hand-gesture-cursor-control.git
   cd hand-gesture-cursor-control
   
2. Install the required Python packages:

Option 1: Using PyCharm (Recommended)
         Open the project in PyCharm.
         Navigate to:
             File > Settings > Project: <your_project_name> > Python Interpreter
         Click the + icon to add the following packages:
           - opencv-python
           - mediapipe 
           - pyautogui
# Usage
1. Open the project in PyCharm.
2. Ensure your webcam is connected and accessible.
3. Run the main script:
4. Place your hand within the camera frame:
- Move your index finger to control the mouse cursor.
- Bring your thumb and index finger close together to simulate a click.

# Requirements
Python 3.x
PyCharm (or any Python IDE)
OpenCV
MediaPipe
PyAutoGUI
Webcam (internal or external)
