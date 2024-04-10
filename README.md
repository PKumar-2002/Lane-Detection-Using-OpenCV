# Real-Time Lane Detection System

Embark on the journey of autonomous driving with our Real-Time Lane Detection System. Utilizing the power of OpenCV and Tkinter, this Python application captures live video feeds to detect and highlight lane markings on the road.

## Features

- **Canny Edge Detection**: Harnesses the Canny algorithm for precise edge detection.
- **Sobel Edge Detection**: Employs Sobel operators to identify horizontal and vertical lane edges.
- **Hough Line Transform**: Detects lane lines even under challenging conditions.
- **Kalman Filter**: Predicts and tracks lane positions dynamically.
- **All-in-One Mode**: A synergistic mode combining all techniques for superior detection accuracy.
- **Tkinter UI**: An intuitive interface to manage detection settings and camera operations.

## Usage

1. Install Python and the required libraries: `tkinter`, `Pillow (PIL)`, `opencv-python (cv2)`, and `numpy`.
2. Execute `Lane_Detection.ipynb` to start the application.
3. Use the "Start Camera" button to begin lane detection.
4. Switch between detection modes (CED, SED, KFR, HTR, AIO) as needed.
5. Explore each mode's specifics with mode-specific buttons.
6. Activate "All-in-One" mode for a comprehensive detection experience.
7. Close the application to end the session.

## Requirements

- **Python**: Version 3.x or higher.
- **OpenCV**: Core library for image processing and lane detection.
- **Tkinter**: For crafting the graphical user interface.
- **Pillow (PIL)**: Manages image display within Tkinter.
- **NumPy**: Handles numerical operations and array manipulations.

## Getting Involved

Contributions are welcome! Whether it's improving algorithms, enhancing the UI, or suggesting new features, your input can drive this project forward.


Join us in advancing the field of lane detection for safer and smarter driving technologies.
