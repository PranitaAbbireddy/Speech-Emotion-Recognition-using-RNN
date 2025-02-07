# Speech Emotion Recognition using RNN

This project focuses on Speech Emotion Recognition (SER) using Recurrent Neural Networks (RNNs). It processes audio input, extracts features, and classifies emotions based on speech patterns using Bi-Directional LSTMs.

## Features
- Voice Recording Input: Users can record a voice sample.
- Feature Extraction: Uses MFCC (Mel-Frequency Cepstral Coefficients) for speech analysis.
- RNN-based Classification: Predicts the emotion from the extracted features.
- Performance Evaluation: Provides accuracy, loss, and a confusion matrix.

## How It Works
### Record and Upload Audio
- Record a short speech sample (.wav format recommended).
- Convert the file into wavelet format.
- Upload it to the system.

## Data Preprocessing Techniques
- Noise reduction and feature extraction (MFCC, spectrogram, etc.).

## Emotion Classification
The processed audio is fed into an RNN model.
- The system predicts the emotion from categories such as:
  - Happy 
  - Sad 
  - Angry 
  - Neutral
  - Calm
  - Fearful
  - Disgusted
  - Surprised

## Result & Evaluation
- The predicted emotion is displayed.
- Evaluation metrics (accuracy, confusion matrix) are provided.

## Installation & Setup
- Clone the Repository
- Install Dependencies
- Run the Application

## Dataset
The project uses RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song). Download the dataset from RAVDESS Official Website.

## Future Improvements
- Add more datasets for better generalization.
- Implement real-time emotion detection.
- Improve UI for user-friendly interactions.

## License
This project is licensed under the MIT License.
