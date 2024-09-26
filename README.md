# Virtual-Mouse


## Virtual Mouse Using OpenCV, MediaPipe, and Autopy

This project implements a virtual mouse using computer vision and hand tracking techniques. The application captures hand movements through a webcam and translates them into mouse movements on the screen. It allows for controlling the mouse pointer and performing click actions using simple hand gestures.

#### 🔧 **Key Features:**
- **Hand Tracking:** Utilizes MediaPipe's hand tracking module to detect and track hand movements in real-time.
- **Cursor Control:** Maps the index finger's position to move the mouse pointer across the screen.
- **Click Action:** Allows clicking actions by detecting the proximity of the index and middle fingers.
- **Smooth Movement:** Implements smooth pointer movement using interpolation and a smoothing factor for precise control.
- **Real-time FPS Display:** Shows the current frame rate on the screen for performance monitoring.

#### 📦 **Technologies Used:**
- **OpenCV**: For video capture and image processing.
- **MediaPipe**: For efficient hand tracking and gesture detection.
- **Autopy**: To control mouse movements and clicks programmatically.
- **NumPy**: For numerical operations.

#### 💻 **How to Run:**
1. Install the required libraries using:
   ```bash
   pip install opencv-python mediapipe autopy numpy
   ```
2. Run the script:
   ```bash
   python virtual_mouse.py
   ```
3. Ensure your webcam is working, and move your hand within the frame to control the mouse pointer.


