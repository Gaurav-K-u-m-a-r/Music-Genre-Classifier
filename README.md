# 🎵 Music Genre Classifier

A Machine Learning project that automatically classifies music tracks into different genres using audio feature extraction and the K-Nearest Neighbors (KNN) algorithm.

## 📌 Overview

Music Genre Classification is a Music Information Retrieval (MIR) task that aims to identify the genre of a music track based on its audio characteristics. This project extracts Mel-Frequency Cepstral Coefficients (MFCCs) from audio files and uses a KNN classifier to predict the genre of a song.

The system analyzes audio signals, extracts meaningful features, and classifies songs into genres such as:

* Blues
* Classical
* Country
* Disco
* Hip-Hop
* Jazz
* Metal
* Pop
* Reggae
* Rock

---

## 🚀 Features

* Audio feature extraction using MFCC
* Genre prediction using K-Nearest Neighbors (KNN)
* Training and testing dataset split
* Audio preprocessing and feature engineering
* Model evaluation using classification accuracy
* Support for WAV audio files
* GTZAN dataset integration

---

## 🛠️ Tech Stack

* Python
* NumPy
* SciPy
* Python Speech Features
* Pickle
* OS
* Random
* Math
* Operator

---

## 📂 Dataset

**Dataset Used:** GTZAN Genre Collection

The GTZAN dataset contains 1000 audio tracks categorized into 10 music genres, with 100 audio samples per genre.

Dataset Structure:

```text
genres_original/
├── blues/
├── classical/
├── country/
├── disco/
├── hiphop/
├── jazz/
├── metal/
├── pop/
├── reggae/
└── rock/
```

---

## ⚙️ Working

1. Load audio files from the dataset.
2. Extract MFCC features from each audio track.
3. Compute statistical representations of extracted features.
4. Store features using Pickle serialization.
5. Split data into training and testing sets.
6. Apply K-Nearest Neighbors classification.
7. Predict the genre of unseen music samples.
8. Evaluate model performance using accuracy metrics.

---

## 📊 Results

The KNN-based Music Genre Classifier achieved an accuracy of approximately:

```text
Accuracy: 69.91%
```

Genre-wise performance showed strong classification results for:

* Hip-Hop
* Folk
* Rock

while Pop music was comparatively harder to classify due to overlapping characteristics with other genres.

---

## 📁 Project Structure

```text
Music-Genre-Classifier/
│
├── Data/
│   └── genres_original/
│
├── Project.ipynb
├── my.dat
├── MGCReport.pdf
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/Gaurav-K-u-m-a-r/Music-Genre-Classifier.git
cd Music-Genre-Classifier
```

### Install Dependencies

```bash
pip install numpy scipy python_speech_features
```

### Run Notebook

```bash
jupyter notebook Project.ipynb
```

Execute all cells to:

* Extract features
* Train the model
* Evaluate accuracy
* Predict genres for new audio samples

---

## 🎯 Future Improvements

* Implement CNN-based Deep Learning models
* Use Spectrogram and Mel-Spectrogram representations
* Improve accuracy with larger datasets
* Build a web-based user interface
* Deploy as a real-time music genre prediction application

---

## 👨‍💻 Author

**Gaurav Kumar**

B.Tech Computer Science & Engineering

Lovely Professional University

GitHub: https://github.com/Gaurav-K-u-m-a-r

---

## 📜 License

This project is developed for educational and learning purposes.
