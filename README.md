# Media-and-ai
Assignments1-3 and MiNi projects
Project Overview:
This project captures video data from a camera using OpenCV and converts it to frames. It uses hand keypoints from the mediapipe library to implement a finger drawing game and rock paper scissors recognition (using the mediapipe dataset).

Installation Instructions:
This program requires OpenCV, the mediapipe library, and the dataset to be installed. Please download the necessary dependencies before running the program.

Usage Instructions:
Press the "s" key to toggle between modes (finger drawing game and rock paper scissors recognition).
Press the "c" key to clear finger tracks.
Press the "q" key to exit the program.

Examples and Demonstrations:See document package for details
Code Explanation:
This program first calls the OpenCV library to capture video data from the camera and then uses the hand keypoints detection algorithm from the mediapipe library to detect hand keypoints and draw them in the video frame. For the finger drawing game, the program tracks finger endpoints and draws finger tracks in the video frame. For rock paper scissors recognition, the program uses a pipe to pass the video frame to the GestureRecognition class, which evaluates the gesture and then uses the DisplayHand class to draw the keypoints and rock paper scissors results in the video frame.
