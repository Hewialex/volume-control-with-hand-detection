# Volume Control with Hand Detection 🎛️
This project enables real-time control of system volume using hand gestures, leveraging computer vision and machine learning. It utilizes OpenCV, MediaPipe, and Pycaw to capture hand landmarks, detect finger distance, and adjust volume accordingly.

## Features
- **Real-Time Volume Control**: Adjust system volume by varying the distance between your thumb and index finger.
- **Interactive Visualization**: Visual indicators show the hand landmarks, connecting lines, and dynamic volume levels.
- **User-Friendly**: Volume level and percentage are displayed, giving immediate feedback on the current volume setting.

## Technologies Used
- **Python**: For core logic and integration
- **OpenCV**: For webcam interaction and real-time video processing
- **MediaPipe**: For hand landmark detection
- **Pycaw**: To control system audio through Python

**How It Works**
- Hand Detection: MediaPipe identifies and tracks hand landmarks, focusing on the thumb and index finger.
- Distance Calculation: The distance between the thumb and index fingertips is calculated in real time.
- Volume Mapping: The finger distance is mapped to the system's volume range using Pycaw, adjusting the volume proportionately.
- Visual Feedback: Visual indicators are drawn on the webcam feed to show the distance between fingers and the current volume level.

**Setup Instructions**
1. Clone the repository
   git clone https://github.com/Hewialex/volume-control-with-hand-detection
2. Install the necessary dependencies
   pip install opencv-python mediapipe pycaw comtypes numpy
3. Run the python script
   python volume_control.py
   
**Usage**

- Open the Webcam Feed: The script will automatically access the webcam.
- Adjust Volume: Bring your thumb and index fingertips closer together to lower the volume and further apart to raise it.
- Exit: Press q to close the webcam feed and exit the application.

**Future Improvements**

- Add support for multi-hand volume control.
- Implement additional gestures to mute or set a specific volume.

**Author**

Hewan Alemayehu
