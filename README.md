
# 🎙️ Speech Emotion Recognition using Wav2Vec 2.0

This project implements a **Speech Emotion Recognition (SER)** system using Facebook AI’s **Wav2Vec 2.0** model. It extracts deep contextual audio embeddings from raw waveform speech data and classifies emotions using a fine-tuned classifier.

---

## 🔍 Overview
Emotion recognition from speech has real-world applications in:
- 🤖 Human-Computer Interaction (empathetic chatbots, voice assistants)  
- 📞 Call Center Analytics (detecting frustration in real-time)  
- 🧠 Mental Health Monitoring (tracking stress & mood changes)  

Traditional SER methods relied on **hand-crafted acoustic features** (MFCCs, pitch, prosody), but this project leverages **self-supervised learning (SSL)** via **Wav2Vec 2.0** for improved robustness and accuracy.

---

## 🚀 Features
- Pretrained Wav2Vec2.0 for extracting audio embeddings  
- Fine-tuned emotion classification head  
- Support for multiple datasets (RAVDESS, Emo-DB, IEMOCAP, etc.)  
- End-to-end pipeline: training → evaluation → inference  
- Visualization of confusion matrix & accuracy curves  

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
