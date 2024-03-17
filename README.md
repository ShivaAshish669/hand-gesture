Hand Gesture Recognition for Drone Control
This project utilizes hand gesture recognition to control a drone using a webcam. Hand gestures are detected in real-time using the MediaPipe library and interpreted as commands for the drone.

Installation
To run this project, you'll need to install the following dependencies:

OpenCV-Python: pip install opencv-python
MediaPipe: pip install mediapipe
TensorFlow: pip install tensorflow
Once the dependencies are installed, you can run the project using the command:

Copy code
python app.py
Usage
Run the Program: Execute the app.py script using the command provided above.
Camera Setup: Ensure your webcam is connected and properly configured.
Hand Gesture Recognition: Hold your hand in front of the camera and perform gestures to control the drone.
Show full palm to stop the drone.
Close the wrist to move the drone.
Rotate the hand to control the drone's rotation.
Exit: Press ESC to exit the program.
Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request.


Acknowledgments
The hand detection and gesture recognition functionality are powered by the MediaPipe library.
Special thanks to the contributors of OpenCV, TensorFlow, and other dependencies used in this project.
