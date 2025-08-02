# 🎵 Moodify – AI-Powered Music Recommender
Moodify is an AI-powered music recommendation system that detects the user’s current emotion from real-time webcam input and suggests mood-appropriate songs.
Using MediaPipe for facial landmark detection, OpenCV for video processing, and Streamlit for the interface, Moodify delivers an interactive, personalized music experience.

## Features
- Real-time emotion detection from live webcam feed

- Facial landmark extraction using MediaPipe

- Emotion classification into categories:
  - Happy
  - Sad
  - Angry
  - Neutral
  - and more...

- YouTube integration for dynamic song recommendations

- User can specify:

  - Language of the song

  - Preferred artist/singer

- Responsive Streamlit UI for smooth user interaction

## Tech Stack
- Python 3.9+
- OpenCV – Video capture & preprocessing
- MediaPipe – Face and landmark detection
- Streamlit – Web interface
- NumPy – Numerical computations
- Webbrowser module – Opens YouTube recommendations

## Usage
- Enter optional language and singer preferences.
- Allow camera access.
- Click “Recommend me songs”.
- Moodify detects your emotion and opens YouTube with mood-aligned song suggestions.
