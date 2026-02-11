<font size="6">**🎵 Music Genre Classification using GTZAN Dataset**</font>

## **1. Introduction**
**📌 Purpose of the Project**

This project focuses on **automatic music genre classification**, a multi-class classification problem in machine learning. Using the **GTZAN dataset**, we explore two different approaches:

- **Tabular feature-based classification** using extracted audio features

- **Image-based classification** using mel-spectrogram images and Convolutional Neural Networks (CNNs)

The goal is to **train, evaluate, and compare** both approaches to understand their effectiveness in classifying music genres.

<br>

## **2. Dataset Overview**
**📂 Dataset Description**

The GTZAN dataset contains audio recordings belonging to **10 music genres**, with 100 samples per genre.

Genres included:

- Blues, Classical, Country, Disco, Hiphop
- Jazz, Metal, Pop, Reggae, Rock

Dataset components used:

- `features_30_sec.csv` → Tabular audio features
- `images_original/` → Mel-spectrogram images for CNN training

<br>

## **3. Environment Setup**
**🔧 Installing Required Libraries**

This cell installs all necessary Python libraries for audio processing, machine learning, and deep learning.

**Explanation:**

- `librosa` is used for audio feature extraction
- `scikit-learn` for classical ML models and evaluation
- `tensorflow / keras` for CNNs
- `seaborn` for visualization
