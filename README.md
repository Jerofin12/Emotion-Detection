# Emotion Detection from Speech and Video
# 📌 Overview
This repository detects human emotions—such as happy, sad, angry, and neutral—from audio extracted from video files. It uses OpenAI Whisper for transcription, Librosa for audio feature extraction, and scikit-learn (SVM) for emotion classification.

# 🎯 Objectives
1.Transcribe speech from video/audio.
2.Extract audio features (MFCC, pitch).
3.Classify the speaker’s emotion.
4.Display the transcription, detected emotion, and spoken language.

# 🧠 Technologies Used
1.Technology	Purpose
2.Whisper	Transcribe speech and detect language
3.Librosa	Extract MFCC and pitch features
4.scikit-learn	Train & apply Support Vector Machine (SVM)
4.moviepy	Convert video files (MP4) to audio (WAV)
5.NumPy	Numerical operations and feature vectors

# 🚀 How It Works
Input: Video/audio file.
Convert: Extract audio from video using moviepy.
Transcribe: Use Whisper to generate transcription and detect language.
Extract Features: Get MFCC and pitch features with Librosa.
Predict Emotion: Use a trained SVM model to classify emotion.
Output: Print transcription, detected emotion, and language.

# 🛠 Installation
# Install Dependencies
Install the required libraries using pip:

pip install openai-whisper librosa scikit-learn moviepy numpy

# 📁 Project Structure

emotion_speech_recognition/
│
├── Emotion Detection.ipynb     # Main script containing all steps
├── Emotion Detection.pptx      # Project slides
├── README.md                   # Project README
├── Emotion Detection           # Project documentation

# Input Link

https://youtube.com/shorts/qe3lzbs47UY?si=N20f5ymqvEahgLrD

# ⚠️ Limitations
Trained on simulated (fake) data, not real emotional recordings.
Detects only 4 basic emotions.
Not suitable for real-time/live input.
Ignores facial expressions and contextual text cues.
Sensitive to background noise.

# 🔮 Future Enhancements
Train on real-world emotional datasets.
Detect more diverse and subtle emotions.
Add real-time processing via microphone.
Combine multimodal inputs: audio, text, video.
Create a user-friendly web interface or API.
Improve multilingual support and personalization.

# 📚 Conclusion
This project demonstrates a foundational approach to emotion detection using audio data. While limited by its training data and emotion scope, it sets the stage for more advanced, real-time, and multimodal emotion-aware systems.


