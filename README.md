# 🎭 Speech Emotion Recognition with Real-Time Visualization

This project is an enhanced **Speech Emotion Recognition (SER)** system that detects human emotions from audio signals using machine learning and deep learning techniques.

It extends an open-source implementation by adding real-time interaction and improved usability.

---

## 🚀 My Contributions

* 🎯 Added **real-time emotion detection using microphone input**
* 😀 Implemented **emoji-based visualization for predicted emotions**
* ⚡ Improved testing workflow for live audio
* 🛠️ Minor preprocessing and output formatting enhancements

These improvements make the system more interactive and suitable for real-time applications like call sentiment monitoring.

---

## 🧠 Project Overview

The system:

* Extracts audio features (MFCC, Chroma, Mel, etc.)
* Trains ML & DL models
* Predicts emotions from speech input
* Supports real-time testing via microphone

---

## 📊 Supported Emotions

* Neutral
* Calm
* Happy
* Sad
* Angry
* Fear
* Disgust
* Surprise
* Boredom

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* TensorFlow / Keras
* Librosa
* NumPy, Pandas
* Matplotlib
* PyAudio

---

## 📂 Datasets Used

* RAVDESS
* TESS
* EMO-DB
* Custom dataset

(All datasets are preprocessed and included in the `data/` directory)

---

## ⚙️ Features

* 🎧 Emotion classification from audio files
* 🔍 Feature extraction (MFCC, Chroma, Mel, Tonnetz, Contrast)
* 🤖 Multiple ML models (SVM, Random Forest, MLP, etc.)
* 🧠 Deep Learning (RNN / LSTM support)
* 📈 Model evaluation (accuracy, F-score, confusion matrix)
* 🎙️ Real-time voice emotion detection

---

## ▶️ How to Run

### 1. Clone repo

```bash
git clone https://github.com/BanalaShiva24/Emotion-Analytics.git
cd Emotion-Analytics
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run real-time testing

```bash
python test.py
```

---

## 📈 Example Result

* Accuracy up to ~89% using MLPClassifier
* Real-time predictions with probability output

---

## 🎯 Use Cases

* Call center sentiment analysis
* Emotion-aware AI systems
* Human-computer interaction
* Mental health monitoring

---

## 🚀 Future Improvements

* Deploy as web app (Streamlit)
* Improve real-time performance
* Add transformer-based models (BERT for audio embeddings)

---

## ⚠️ Note

This project is based on an open-source implementation and extended with additional features for better usability and real-time interaction.

---

## ⭐ If you found this useful, give it a star!
