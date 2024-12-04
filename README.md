
# Sign Language Detection Using Tkinter

A desktop application for detecting and converting sign language gestures into text and speech using a machine learning model. This project employs **Tkinter** for the GUI, along with various libraries for image processing, machine learning, and text-to-speech conversion.

## Features
1. Real-time hand detection using OpenCV and CvZone.
2. Gesture-to-text conversion with a trained Keras model.
3. Text-to-Speech conversion using Pyttsx3.
4. Language validation using Enchant for accurate word detection.

## Technologies Used

### Machine learning
1. **Keras**: Loads and runs the pre-trained model.
2. **NumPy**: Handles numerical operations for image processing.
### Computer Vision
1. **OpenCV**: Captures and processes images from the webcam.
2. **CvZone** HandDetector: Detects hands and fingers in real-time.
### Text & Speech
1. **Pyttsx3**: Converts detected sign language into speech.
2. **Enchant**: Validates the detected text.
### Frontend
1. **Tkinter**: Provides a user-friendly desktop GUI.
2. **Pillow (PIL)**: Manages image rendering and display in the GUI.
