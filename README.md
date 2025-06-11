# Hand-Gesture-Recognition-using-Python
A Python-based hand gesture recognition system using OpenCV and MediaPipe. Detects 1–4 finger gestures in real time via webcam and opens corresponding websites: 1 for Web WhatsApp, 2 for Instagram, 3 for Facebook, and 4 for Google. Useful for hands-free web control and automation tasks.



🧠 Overview:
Hand Gesture Recognition is a computer vision-based project that identifies and interprets human hand gestures using machine learning and image processing techniques. The system is capable of analyzing real-time video input, detecting hand regions, recognizing specific gestures, and mapping them to predefined actions.

💡 Objective:
To build an intelligent interface that can recognize various hand gestures using a webcam, enabling applications such as virtual mouse control, sign language translation, and gesture-based navigation.

⚙️ Tech Stack:
Programming Language: Python

Libraries/Tools: OpenCV, Mediapipe, NumPy, TensorFlow/Keras (if using ML model), Scikit-learn (for classical ML models), PyAutoGUI (for controlling actions like mouse clicks, keyboard events)

IDE: Jupyter Notebook / VS Code

Hardware: Webcam

🧱 Key Components:
Hand Detection: Using Mediapipe or Haar Cascades to locate the hand in the frame.

Gesture Classification:

Static gestures: Based on hand landmarks and finger positions.

Dynamic gestures (optional): Based on movement over time.

Action Mapping: Map recognized gestures to real-world tasks like:

Controlling a media player

Navigating slides

Simulating mouse/keyboard actions

User Interface (Optional): Basic UI using Tkinter or Streamlit to show detected gesture live.

🎯 Applications:
Sign language recognition

Touchless device control

Interactive games

Smart home interfaces

Accessibility tools

🧠 Skills Gained:
Real-time computer vision with OpenCV and Mediapipe

Landmark detection and preprocessing

Gesture classification logic

Integration with system-level controls using PyAutoGUI

Understanding of image features and ML basics

📌 Sample Output:
Live webcam feed with hand detection and gesture label

Virtual buttons triggered by specific gestures

Mouse pointer control with finger tracking

