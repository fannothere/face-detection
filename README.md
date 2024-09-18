# Face Detection using OpenCV
This project demonstrates face detection using the OpenCV library in Python. It captures video from a webcam and detects faces in real-time using Haar Cascade classifiers.

# Features
<ul>
<li>Real-time face detection: Detects faces in a live video stream using your webcam.</li>
<li>Multi-face detection: Supports detection of multiple faces simultaneously in one frame.</li>
  </ul>
  
# Prerequisite
Before running the program, ensure that you have the following installed:
<ol>
<li>Python (version 3.6 or above)</li>
<li>OpenCV: The OpenCV Python library for image processing.</li>
</ol>

# Installing OpenCV
You can install OpenCV using pip:

```
pip install opencv-python
```

You will also need the Haar Cascade classifier XML file for face detection. OpenCV provides a pre-trained model for this, and it can be found in the OpenCV repository.

Download the classifier from this link or use the default path in OpenCV:

```
cv2.data.haarcascades + 'haarcascade_frontalface_default.xml
```

# How to Run
Clone the repository or download the Python script.
Ensure that OpenCV is installed using the command pip install opencv-python.
Run the Python script:
bash

```
python app.py
```

The webcam will start, and the program will display the video feed with rectangles drawn around any detected faces. Press ```q``` to quit the program.
