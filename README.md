
# Sign Language Detector

The Sign Language Detector is an innovative project that combines machine learning, computer vision, and Python programming to recognize and interpret sign language gestures in real-time. It offers a practical solution for communication accessibility or educational purposes, enabling users to interact with sign language through a webcam feed.

## Project Overview

The Sign Language Detector project is designed to recognize and interpret sign language gestures, making it accessible and educational for those interested in the field. It leverages machine learning techniques to classify hand gestures into predefined sign language letters.

## How it Works

1. **Data Collection:** The project collects data for sign language gestures using a webcam. It captures images of hand gestures for different letters of the sign language alphabet.

2. **Training:** The collected data is used to train a machine learning model. The model is trained to recognize and classify hand gestures based on the landmarks detected in the images.

3. **Real-time Detection:** The trained model is then used for real-time detection of sign language gestures through a webcam feed. It processes the video frames, detects hand landmarks, and predicts the corresponding sign language letter.

4. **Display:** The predicted sign language letter is displayed on the screen in real-time, providing a practical application for communication accessibility or educational purposes.


## Usage

To use this Sign Language Detector:

1. Clone the repository to your local machine.
2. Ensure you have the required libraries installed (OpenCV, Scikit Learn, Mediapipe).
3. Train the model using the data_collection.py script to create and save a dataset.
4. Run the sign_language_detector.py script to start real-time sign language detection.


## License

This project is open-source and available under the [MIT License](LICENSE).
