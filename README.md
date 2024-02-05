
# Sign Language Detector

This project is a Sign Language Detector developed using Python and Scikit Learn for computer vision techniques. It allows real-time sign language gesture recognition through a webcam feed.

## Project Overview

The Sign Language Detector project is designed to recognize and interpret sign language gestures, making it accessible and educational for those interested in the field. It leverages machine learning techniques to classify hand gestures into predefined sign language letters.

## How it Works

1. **Data Collection:** The project collects data for sign language gestures using a webcam. It captures images of hand gestures for different letters of the sign language alphabet.

2. **Training:** The collected data is used to train a machine learning model. The model is trained to recognize and classify hand gestures based on the landmarks detected in the images.

3. **Real-time Detection:** The trained model is then used for real-time detection of sign language gestures through a webcam feed. It processes the video frames, detects hand landmarks, and predicts the corresponding sign language letter.

4. **Display:** The predicted sign language letter is displayed on the screen in real-time, providing a practical application for communication accessibility or educational purposes.

## Repository Structure

- `sign_language_detector.py`: Contains the main code for real-time sign language detection.
- `data_collection.py`: Script to collect and save dataset images of sign language gestures.
- `data.pickle`: Pickle file containing the preprocessed dataset.
- `./data/`: Directory where collected dataset images are stored.
- `./model.p`: Pickle file containing the trained machine learning model.

## Usage

To use this Sign Language Detector:

1. Clone the repository to your local machine.
2. Ensure you have the required libraries installed (OpenCV, Scikit Learn, Mediapipe).
3. Train the model using the data_collection.py script to create and save a dataset.
4. Run the sign_language_detector.py script to start real-time sign language detection.


## License

This project is open-source and available under the [MIT License](LICENSE).
