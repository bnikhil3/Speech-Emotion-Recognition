
# 🎙️ Speech Emotion Recognition using Wav2Vec 2.0

This project implements a **Speech Emotion Recognition (SER)** system using Facebook AI’s **Wav2Vec 2.0** model. It extracts deep contextual audio embeddings from raw waveform speech data and classifies emotions using a fine-tuned classifier.

## 🔍 Overview

Emotion recognition from speech has broad applications in **human-computer interaction**, **call center analysis**, **mental health monitoring**, and more. Traditional models rely on hand-crafted acoustic features, but this project uses **self-supervised representation learning** via Wav2Vec 2.0 for superior performance.

---

## 🎧 Dataset

This project supports datasets such as:

* **RAVDESS**
* **CREMA-D**
* **TESS**
* **Emo-DB**


---

## 🧠 Model Architecture

* **Wav2Vec 2.0 (pretrained)** is used to extract 768-dim speech embeddings.
* A lightweight classifier (e.g., MLP or GRU) is trained on top of the frozen/finetuned embeddings.
* Emotions are predicted as a multi-class classification task.

---

## 📊 Evaluation Metrics

* Accuracy
* F1-Score (macro & weighted)
* Confusion Matrix
* Per-class precision and recall

---

## 🧪 Results

<img width="170" height="132" alt="image" src="https://github.com/user-attachments/assets/5434dcde-b2fc-4752-b6c1-725cd67ba771" />


---

## 🚀 Future Work

* Integrate real-time emotion prediction
* Expand to multilingual emotion detection
* Use attention-based architectures for better temporal modeling

---

## 📚 References

* [Wav2Vec 2.0: Facebook AI](https://arxiv.org/abs/2006.11477)
* HuggingFace Transformers
* torchaudio, librosa

---
