Sign Language Detection using Tkinter
A desktop application that detects sign language from images and converts it into text and speech using a machine learning model. This project uses Tkinter for the user interface, integrating various libraries for image processing, machine learning, and text-to-speech.

Features
Real-time hand detection and tracking using OpenCV and CvZone.
Conversion of detected hand signs into text using a trained Keras model.
Text-to-Speech functionality using Pyttsx3.
Language validation using Enchant to ensure accurate word detection.
Technologies Used
Machine Learning:
Keras: Loads the pre-trained model for sign language detection.
NumPy: Handles numerical operations for image processing.
Computer Vision:
OpenCV: Captures and processes images from the webcam.
CvZone HandDetector: Detects hands and fingers in real-time.
Text and Speech:
Pyttsx3: Converts detected sign language into speech.
Enchant: Validates the detected text for accuracy.
Frontend:
Tkinter: Builds the GUI for a user-friendly desktop application.
PIL (Pillow): Manages image rendering and display in the GUI.
