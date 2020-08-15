
This HCI (Human-Computer Interaction) application in Python(3.6) will allow you to control your mouse cursor with your facial movements, works with just your regular webcam. Its hands-free, no wearable hardware or sensors needed.



## Code Requirements
* Numpy - 1.13.3
* OpenCV - 3.2.0
* PyAutoGUI - 0.9.36
* Dlib - 19.4.0
* Imutils - 0.4.6

Tracks facial movements of user and perform specific mouse functionalities.

Identifies facial landmarks through Dlib and controls the mouse pointer through tip of nose.

Uses HOG based face recognition and OpenCV for image processing.

Download the model from dlib site for the pre-trained model of landmarks and place it in model folder.
