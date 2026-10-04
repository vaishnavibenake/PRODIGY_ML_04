# PRODIGY_ML_04 – Hand Gesture Recognition

## Internship
Prodigy InfoTech – Machine Learning Internship

## Task 04

Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

## Dataset

LeapGestRecog – Hand Gesture Recognition Database

Dataset:
https://www.kaggle.com/gti-upm/leapgestrecog

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Google Colab

## Model

A Convolutional Neural Network (CNN) was developed to classify 10 different hand gestures:

- Palm
- L
- Fist
- Fist Moved
- Thumb
- Index
- OK
- Palm Moved
- C
- Down

## Preprocessing

- Images were converted to grayscale.
- Images were resized to 64 × 64 pixels.
- Pixel values were normalized.
- Training, validation, and testing datasets were created.
- Subject-wise splitting was used to reduce data leakage.

## Evaluation

The model was evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix
- Sample Predictions

## Conclusion

This project demonstrates the application of Convolutional Neural Networks for hand gesture recognition and gesture-based human-computer interaction.