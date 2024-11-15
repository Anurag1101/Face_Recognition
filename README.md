# Face Recognition Using OpenCV

## Overview

This project demonstrates a simple face detection system using `OpenCV's` Haar cascade classifier. The system detects faces in an image and highlights them with rectangles.

Features
Loads an image and resizes it for optimal performance.
Converts the image to grayscale for better face detection.
Detects faces using the Haar cascade classifier.
Highlights detected faces with bounding rectangles.
Technologies Used
Python: For scripting and image processing.
OpenCV: For face detection and image manipulation.
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/Face_Recognition.git
cd Face_Recognition
Install Dependencies Ensure you have Python installed. Then, install OpenCV:

bash
Copy code
pip install opencv-python
Download Haar Cascade File Download the haarcascade_frontalface_default.xml file from the OpenCV GitHub repository and place it in the project directory.

Usage
Replace 1.jpg in the script with the path to your desired image.
Run the script:
bash
Copy code
python face_recognition.py
The program will display the input image with detected faces highlighted.
Example Output
After running the script, you will see the image with bounding rectangles around detected faces.

Project Structure
bash
Copy code
Face_Recognition/
├── face_recognition.py          # Main script for face detection
├── haarcascade_frontalface_default.xml  # Haar cascade file for face detection
└── 1.jpg                        # Sample image (replaceable)
Future Enhancements
Add functionality to detect faces in real-time using a webcam.
Integrate advanced face recognition models like deep learning-based detectors.
Improve the UI for displaying results.
License
This project is licensed under the MIT License. See the LICENSE file for details.
