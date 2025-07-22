# 🎵 Emotify – Emotion-Based Music Suggestion System

**Emotify** is a Python project that detects facial emotions in real time using a webcam and suggests mood-aligned Hindi songs using the Spotify Web API.

## 🔧 Features
- Real-time emotion detection using OpenCV and a CNN model, trained on FER dataset with 6 emotions
- Live webcam feed with emotion labels
- Song selection based on emotion using Spotipy (Spotify API)
- Decision Tree Classifier trained on audio features with 97% F1-score
- Either suggest songs from our custom Hindi songs playlist, or classify songs from a Spotify playlist link input by user

## 🛠️ Tech Stack
- Python, Keras, OpenCV
- Spotipy (Spotify Web API)
- Pandas, NumPy, Scikit-learn

## 🚀 How to Run
1. Clone the repo and install dependencies  
2. Set up Spotify API credentials  
3. Run the script to start webcam-based emotion detection and music playback

## [Dataset Link](https://www.kaggle.com/datasets/msambare/fer2013)
## Important Update -
Unfortunately, the features used from Spotipy have now been deprecated by the company. So the project will no longer run on new data. This is the only working notebook with output. 
