Lane Detection using OpenCV and Tkinter

This project implements a real-time lane detection system using OpenCV and Tkinter in Python. It detects lanes from a live video feed captured by a camera and applies various image processing techniques to highlight the lanes.

>>Features

->Canny Edge Detection: Detects edges in the image using the Canny edge detection algorithm.

->Sobel Edge Detection: Implements edge detection using Sobel operators for horizontal and vertical gradients.

->Hough Line Transform: Utilizes the Hough line transform to detect lines in the edge-detected image.

->Kalman Filter: Implements a Kalman filter to predict and track the position of lane lines over time.

->All-in-One Mode: Combines all the above techniques to detect and track lanes in a single mode.

->User Interface with Tkinter: Provides a simple GUI interface to start the camera and toggle between different detection modes.

>>Usage

1. Ensure you have Python installed on your system along with the necessary libraries (tkinter, PIL, cv2, numpy).

2. Run the lane_detection.py script using a Python interpreter.

3. Click on the "Start Camera" button to initiate the camera feed.

4. Toggle between different lane detection modes using the provided buttons (CED, SED, KFR, HTR, AIO).

5. Optionally, click on the mode-specific buttons to display information about each technique.

6. Press the "AIO" button to activate the All-in-One mode for comprehensive lane detection.

7. Close the application window to stop the camera feed and exit the program.

>>Requirements

->Python 3.x

->OpenCV (cv2)

->Tkinter

->PIL (Python Imaging Library)

->NumPy
