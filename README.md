# Speech Emotion Recognition (SER)

## Project Overview

Speech Emotion Recognition (SER) is an Artificial Intelligence and Machine Learning project that identifies human emotions from speech recordings.

The system analyzes audio signals and extracts important voice features to recognize different emotions such as Happy, Sad, Angry, Neutral, Fearful, Disgust, and Surprised.

This project uses the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset to train and evaluate emotion classification models.

##  Project Objectives

- Recognize human emotions from voice recordings.
- Extract meaningful features from audio signals.
- Perform audio preprocessing and feature extraction.
- Train Machine Learning and Deep Learning models.
- Compare model performance and accuracy.
- Predict emotions from new audio recordings.

##  Technologies Used

- Python
- NumPy
- Pandas
- Librosa
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

##  Dataset

**RAVDESS – Ryerson Audio-Visual Database of Emotional Speech and Song**

The dataset contains audio recordings representing different emotional expressions.

Emotions included:

- 😠 Angry
- 😊 Happy
- 😢 Sad
- 😐 Neutral
- 😨 Fearful
- 🤢 Disgust
- 😲 Surprised
- Calm

##  Feature Extraction

The following audio features are extracted:

- MFCC (Mel-Frequency Cepstral Coefficients)
- Zero Crossing Rate (ZCR)
- Chroma Features
- RMS Energy
- Mel Spectrogram

These features help the model understand different characteristics of human speech.

##  Machine Learning Models

The project explores multiple classification algorithms:

- Logistic Regression
- Support Vector Machine (SVM)
- AdaBoost
- XGBoost
- Long Short-Term Memory (LSTM)

##  Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 58.56% |
| SVM | 59.26% |
| AdaBoost | 40.97% |
| XGBoost | 35.94% |
| LSTM | 61.21% |

SVM achieved 59.26% accuracy among the classical Machine Learning models, while LSTM achieved 61.21%.

##  Key Features

- Audio data preprocessing.
- Feature extraction from speech recordings.
- Emotion classification.
- Model comparison and evaluation.
- Prediction of emotions from new audio samples.

##  Future Improvements

- Develop a real-time speech emotion recognition system.
- Build a web application using Flask.
- Improve prediction accuracy.
- Integrate microphone-based live audio detection.
- Explore advanced Deep Learning architectures.

##  Author

**Moses Raj**

GitHub: https://github.com/Moses360-co

LinkedIn: https://www.linkedin.com/in/moses-raj-b10525233/

---

⭐ If you find this project interesting, please give the repository a star!
