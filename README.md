# 🧠 EEG Brainwave Emotion Classifier

This project uses EEG data to classify human emotions using a neural network built with TensorFlow/Keras. The data is sourced from the [EEG Brainwave Dataset: Feeling Emotions](https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions).

---

## 📊 Dataset Overview

- **Samples:** 2132
- **Features:** 2548 EEG features (e.g., channel-frequency combinations)
- **Target Labels:** 3 emotions:
  - `NEUTRAL`: 716 samples
  - `NEGATIVE`: 708 samples
  - `POSITIVE`: 708 samples

---

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Hacxmr/eeg-brain-wave.git
cd eeg-brain-wave

## 🚀 Model Performance

| Model                          | Accuracy   |
|--------------------------------|------------|
| Random Forest                  | 98.83%     |
| Support Vector Machine (SVM)   | 95.78%     |
| Neural Network                 | 98.59%     |

