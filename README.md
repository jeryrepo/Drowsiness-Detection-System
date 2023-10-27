# Drowsiness Detection Using Facial Landmarks
Computer Vision Project

## Overview

Python script leverages OpenCV, dlib, and imutils to monitor a person's drowsiness by analyzing their eye blinking patterns. The code continuously captures video from the default camera and assesses the blinking behavior to determine if the individual is alert, drowsy, or asleep. Detailed Explanation video of the project : https://www.youtube.com/watch?v=O82pYYSgDvw

## Prerequisites

Before you can run this script, ensure you have the following prerequisites in place:

- **OpenCV**: Install OpenCV, a popular computer vision library, which is used for video capture and image processing.

    You can install it using pip:
    ```
    pip install opencv-python
    ```

- **dlib**: This library is used for face detection and facial landmark identification. You can install it with pip as well.

    ```
    pip install dlib
    ```

- **imutils**: Imutils is a set of convenience functions for OpenCV. You can install it via pip.

    ```
    pip install imutils
    ```

## Installation

1. **Clone or Download**: Clone this repository or download the script to your local machine.

2. **Download Face Landmark Model**: You need the "shape_predictor_68_face_landmarks.dat" file for facial landmark detection. Download the model from [this link](https://drive.google.com/file/d/1grO8oD92YqFQm9vYem-RHTdBRkexfz46/view?usp=sharing) and place it in the same directory as the script.

## How to Run

Follow these steps to run the drowsiness detection script:

1. **Open Terminal/Command Prompt**: Open a terminal or command prompt.

2. **Navigate to the Script Directory**: Use the `cd` command to navigate to the directory where the script is located.

3. **Run the Script**: Execute the script by running the following command:

    ```
    python drowsiness_detection.py
    ```

4. **Monitor Video Feed**: The script will open the video feed from the default camera. It will continuously analyze the person's eye blinking patterns.

5. **Check Status**: The status (active, drowsy, or sleeping) will be displayed on the video feed.

6. **Exit the Script**: To exit the script, simply press the 'Esc' key.
