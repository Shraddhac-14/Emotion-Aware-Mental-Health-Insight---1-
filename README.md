# Emotion-Aware Mental Health Insight System – Part 1: Speech Emotion Recognition

This repository contains the **Speech Emotion Recognition** module, the first core component of the **Emotion-Aware Mental Health Insight System**.
The complete system combines **speech emotion recognition** with **sentiment analysis of social media posts** to detect signs of mental health struggles, identify emotional trends, and provide actionable insights for mental health awareness.

In the broader project, speech-based emotion detection works alongside a **BERT-powered text sentiment analysis tool** to classify emotions into **8 distinct categories** with up to **92% accuracy**. This repository focuses on the **speech analysis** side of the system.

---

## Overview

This module classifies emotions from speech by analyzing vocal characteristics such as **pitch**, **tone**, **frequency**, and **modulation**.
It extracts advanced audio features, applies machine learning algorithms, and visualizes results, providing a strong foundation for detecting emotional states in voice recordings.

---

## Features

* **Emotion Classification** – Detect and classify speech into **eight distinct emotional tones**.
* **Vocal Feature Analysis** – Leverage pitch, tone, frequency, and modulation to identify emotional nuances.
* **Statistical Analysis** – Apply in-depth statistical evaluations to improve prediction accuracy.
* **Emotional Classification Graphs** – Visualize detected emotions from speech patterns.

---

## Key Methodologies

### 1. Feature Extraction

* Extract audio features such as:

  * **MFCCs** (Mel-Frequency Cepstral Coefficients)
  * **Chroma Features**
  * **Spectral Contrast**
* Capture speech characteristics for accurate emotion modeling.

### 2. Machine Learning Algorithms

* Train and evaluate ML models for multi-class emotion classification.
* Optimize performance through hyperparameter tuning and feature engineering.

### 3. Statistical Analysis

* Perform detailed statistical computations to enhance reliability of predictions.

### 4. Visualization

* Generate intuitive graphs to display emotional distributions from speech samples.

---

## Technologies Used

* **Python** – Core development language
* **Librosa** – Audio signal processing & feature extraction
* **Pandas** – Data handling & analysis
* **Scikit-learn** – Machine learning implementation
* **Matplotlib / Seaborn** – Visualization

---

## Applications

* Enhancing emotional awareness in **virtual assistants**
* Providing **emotional analytics** for customer support systems
* Supporting **mental health monitoring** through voice patterns
* Feeding into the **Emotion-Aware Mental Health Insight System** for cross-modal emotional trend analysis

---

## Usage

Clone the repository:

```bash
git clone https://github.com/your-username/speech-emotion-recognition.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Prepare your dataset and ensure it’s accessible for feature extraction and training.

---

## Contributions

We welcome contributions!
Ways to contribute:

* Improve feature extraction methods
* Add support for more emotions or languages
* Enhance accuracy of classification algorithms

---

*This is Part 1 of the **Emotion-Aware Mental Health Insight System**, which also includes a BERT-based text sentiment analysis tool for social media posts to detect early signs of mental health struggles.*
