# Hand-Landmark-Detection-Using-OpenCV-and-Tensorflow

This project uses mediapipe which is a Framework for building machine learning pipelines for processing time-series data like video, audio, etc. This cross-platform Framework works in Desktop/Server, Android, iOS, and embedded devices like Raspberry Pi and Jetson Nano.

The hand points detected through mediapipe is stored in an empty list as x and y coordinates.

This is where tensorflow’s deep learning component “keras” comes in.

OpenCV is used to acces the machines camera setup for parsing the video through mediapipe

# Directions

Launch the hand_gesture_detection.py file and input the file (gesture.names) to the names object in the code for detecting the hand signs.
Note that a user can also change the name of signs as per to their meaning.

Press Q to exit out of the prediction window.

# Workflow

1. Initializing the computer vision algorithm

2. Recognizing the hand points and reading the frames from webcam using Mediapipe
  
3. Storing the hand points coordinates  in a list

4. Recognizing the hand gestures by using the training model

5. Predicting the hand signs by tensorflow
