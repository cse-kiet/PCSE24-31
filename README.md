# Hand Gestures Recognition System
## Overview
This repository contains a Hand Gestures Recognition System that utilizes MediaPipe for keypoints detection, OpenCV for object detection, and Handsfree.js for hand landmarks. The system is designed to recognize various hand gestures and can be used for applications such as controlling applications with hand movements, sign language recognition, and more.

## Features

Hand Keypoints Detection: Utilizes MediaPipe to detect and track hand keypoints.
Object Detection: Uses OpenCV for detecting objects within the video stream.
Hand Landmarks: Employs Handsfree.js to extract detailed hand landmarks.
Real-time Processing: Processes video streams in real-time to recognize hand gestures.
Cross-platform: Works on various platforms including Windows, macOS, and Linux.

## Installation

### Prerequisites

Python 3.6 or higher
VS Code
npm
OpenCV
MediaPipe
Handsfree.js

## Setup
### Clone the repository:

bash
Copy code
git clone https://github.com/Jaspreet1616/vision-quest.git

cd vision-quest

Install Python dependencies:

Create and activate a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

### Install required packages:


bash
Copy code
npm install
Usage
Running the System
Start the Python backend:

bash
Copy code
python fast_detection.py
This will start the backend server that handles object detection using OpenCV and keypoints detection with MediaPipe.

### Start the frontend:

Open index.html in your browser. This file includes the integration with Handsfree.js for hand landmarks detection.

Customizing Gestures
To add or modify gestures, update the handsfreejstest.js file with the corresponding hand landmarks and logic.

## File Structure
#### perl
#### Copy code
#### vision-quest/
#### ├── beta
#### │   ├──javascript
#### │   │   ├──bodypose_test.html
#### │   │   ├──handsfreetest.js
#### │   ├── styles.css

#### │   ├── python # Main python code
#### │   │   ├── testing
#### │   │   ├  ├── img_labelled_detection.py
#### │   │   ├  ├── text_labelled_detection.py



#### ├── styles/
#### │   ├── styles.css       # CSS for styling the frontend

#### ├── stable # Main working
#### │   ├── haandsfreetest.js #Javascript code for defining gestures
#### │   ├── index.html #Frontend HTML File
#### ├── README.md            # This README file

### Contributing
#### Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and include appropriate tests.

#### License
#### This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
MediaPipe
OpenCV
Handsfree.js

#### Contact
For any questions or suggestions, please open an issue or contact the repository owner at harshvardhan200216@gmail.com or js7990382@gmail.com.

This README provides a comprehensive guide to setting up and using the Hand Gestures Recognition System. If you encounter any issues, please refer to the documentation or seek assistance through the provided contact information.


