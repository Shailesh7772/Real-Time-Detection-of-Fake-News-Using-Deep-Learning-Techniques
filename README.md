# 📰 Real-Time Fake News Detection using Deep Learning  
### 📍 Presented at IEEE Conference – Manipal Institute of Technology, Bengaluru

![IEEE Certificate](link-to-image-if-public)

---

## 📘 Project Summary

The increasing spread of misinformation poses a serious threat to public discourse and digital trust. This project presents a **deep learning-based system** for **real-time detection of fake news articles**, employing and comparing four cutting-edge models:

- 🔁 **LSTM**
- 🧠 **ALBERT (A Lite BERT)**
- 🌀 **CNN + RNN Hybrid**
- 🔒 **FNNet (Feedforward Neural Network)**

Our system demonstrates exceptional accuracy, especially with ALBERT and CNN+RNN, enabling fast and reliable classification of news articles as **real** or **fake**.

---

## 📊 Experimental Results

### ✅ Model Performance Summary

| Model         | Dataset           | Accuracy | Precision | Recall | F1-Score |
|---------------|-------------------|----------|-----------|--------|----------|
| **ALBERT**     | ISOT              | 100%     | 1.00      | 1.00   | 1.00     |
|               | Fake News         | 100%     | 1.00      | 1.00   | 1.00     |
|               | Real or Fake      | 100%     | 1.00      | 1.00   | 1.00     |
|               | FakeNews Detection| 100%     | 1.00      | 1.00   | 1.00     |
| **LSTM**       | ISOT              | 100%     | 0.99      | 0.99   | 0.99     |
|               | Fake News         | 100%     | 0.97      | 0.97   | 0.97     |
|               | Real or Fake      | 100%     | 0.77      | 0.77   | 0.77     |
|               | FakeNews Detection| 84.79%   | 0.85      | 0.85   | 0.85     |
| **CNN + RNN**  | ISOT              | 99%      | 1.00      | 1.00   | 1.00     |
|               | Fake News         | 99%      | 0.98      | 0.98   | 0.98     |
|               | Real or Fake      | 100%     | 1.00      | 1.00   | 1.00     |
|               | FakeNews Detection| 100%     | 1.00      | 1.00   | 1.00     |
| **FNNet**      | ISOT              | 100%     | 0.99      | 0.99   | 0.99     |
|               | Fake News         | 100%     | 0.99      | 0.99   | 0.99     |
|               | Real or Fake      | 79%      | 0.79      | 0.79   | 0.79     |
|               | FakeNews Detection| 93%      | 0.93      | 0.93   | 0.93     |

---

## 🧠 Deep Learning Models

- **ALBERT**: Best-performing transformer model (100% accuracy on all datasets)
- **LSTM**: Strong temporal dependency learning
- **CNN + RNN**: Excellent spatial + sequential extraction
- **FNNet**: Combines features from all models

---

## 🧪 Sample Predictions

### 🔹 Real News Sample

> _"The state government is nearing the final stages of selecting a site for Bengaluru’s second international airport..."_

| Model     | Prediction |
|-----------|------------|
| LSTM      | ❌ Fake     |
| ALBERT    | ✅ True     |
| CNN+RNN   | ✅ True     |
| FNNet     | ✅ True     |

### 🔹 Fake News Sample

> _"Fred Rogers served as a sniper during the Vietnam War and had a large number of confirmed kills..."_

| Model     | Prediction |
|-----------|------------|
| LSTM      | ✅ Fake     |
| ALBERT    | ✅ Fake     |
| CNN+RNN   | ✅ Fake     |
| FNNet     | ✅ Fake     |

---

## 🧰 Dataset Sources

- [🗂 ISOT Fake News Dataset](https://www.uvic.ca/engineering/ece/isot/datasets/fake-news/index.php)
- [📰 Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- [📄 Fake News Detection Dataset](https://www.kaggle.com/datasets/snapcrack/all-the-news)

---

## 🔧 Methodology

- ✅ Data Cleaning and Tokenization
- ✅ Word Embedding (Word2Vec, GloVe, FastText)
- ✅ Model Training and Cross Validation
- ✅ Evaluation with Accuracy, Precision, Recall, F1-score
- ✅ Real-time Testing & Prediction
- ✅ Confusion Matrices and Visual Metrics

---

## 📌 IEEE Status

This paper was **officially accepted and presented** at the **IEEE Conference hosted by MIT Bengaluru (Manipal Institute of Technology)**.  
The paper is currently published in the IEEE Xplore Digital Library.

---

## 👥 Authors

- **Shailesh K R** – [krshailesh627@gmail.com](mailto:krshailesh627@gmail.com)  
- **Praveen Nandan K**
- **Pakruddin B**
- **Syed Afridi**
- **Shubam V Patil**

Presidency University, Bengaluru  
Department of Computer Science & Engineering

---

## 📄 License

This repository is shared for academic, research, and educational purposes only.  
For citations or collaborations, please contact the corresponding author.

---

## 💡 Future Work

- Integration with browser extensions and APIs for **live fake news detection**
- Expand to multilingual fake news detection (e.g., Hindi, Kannada)
- Benchmark against new transformer models (e.g., RoBERTa, DeBERTa, TimeGPT)

