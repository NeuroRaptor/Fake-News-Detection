
# 📰 Fake News Detection using NLP and Machine Learning

![Status](https://img.shields.io/badge/Stage-Model%20Development-blue)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## 📍 Live Demo

🔗 Try it here: [https://fakenewsdetect-yhif.onrender.com](https://fakenewsdetect-yhif.onrender.com)

---

## 📌 Project Overview

This capstone project focuses on **detecting fake news** using Natural Language Processing (NLP) and classical machine learning algorithms. With the rise of misinformation online, this project aims to provide an automated pipeline that identifies whether a news article is **real or fake**. Compared Classical Machine Learning models, Deep Learning models and Transormer based models.

The final deployed model uses **Support Vector Machine (SVM)** based on its superior accuracy and F1 score across all models tested.
The selected model is exported and deployed separately via Flask in the [FakeNewsDetect](https://github.com/NeuroRaptor/FakeNewsDetect).

---

## 🎯 Objective

- Preprocess and analyze news data using NLP.
- Compare different ML and DL models for classification.
- Deploy the best model (SVM) using a Flask app.
- Build a user-friendly interface for public testing.

---

## 🗂️ Repository Structure

```
📦 Fake-News-Detection/
├── data/              # Raw and cleaned datasets
├── models/            # Trained and exported models (e.g., .pkl, .joblib)
├── notebooks/         # Jupyter notebooks for Pre-processing, EDA and training
├── references/        # Research papers or reference materials
├── reports/           # Visualizations, performance results
├── venv/              # Virtual environment (optional/local)
├── .gitignore         # Files to exclude from Git
├── LICENSE            # Project license (MIT)
├── README.md          # This file
└── requirements.txt   # Python dependencies
```

---

## 📊 Model Performance

| Model       | Accuracy | F1 Scoren|
|-------------|----------|----------|
| **SVM**     | 0.865    | 0.862    |
| CNN         | 0.849    | 0.849    |
| LSTM        | 0.846    | 0.846    |
| BERT        | 0.760    | 0.740    |

**SVM was deployed** as the most effective model for this use case.

---

## 🧪 Models Evaluated

- ✅ **Support Vector Machine (SVM)**
- Naive Bayes
- Logistic Regression
- Random Forest
- LSTM
- CNN
- BERT

---

## 🔧 Technologies Used

- **Python**
- **Flask**
- **Render** (Deployment)
- **scikit-learn**, **NLTK**, **Pandas**, **Matplotlib**, **Seaborn**
- **Keras**, **TensorFlow**
- **Git**, **GitHub**

---

## 📁 Dataset

 1. [LIAR Dataset](https://sites.cs.ucsb.edu/~william/data/)
 2. [FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet)
 3. [ISOT Dataset](https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/)

---
## 📚 References

You can find supporting research materials and paper summaries in the `/references` folder.

---

## 📤 Model Deployment

The trained and selected model (`svm_model.pkl`) is deployed using Flask in the following repository:

🔗 [FakeNewsDetect](https://github.com/NeuroRaptor/FakeNewsDetect)  
Live at: [https://fakenewsdetect-yhif.onrender.com](https://fakenewsdetect-yhif.onrender.com)

---


## 🧪 How to Re-run Experiments

1. **Clone the repository**
```bash
git clone https://github.com/NeuroRaptor/Fake-News-Detection.git
cd Fake-News-Detect
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Open the notebooks**  
Run and modify the training notebooks inside `/notebooks` as needed.

---

## 🎓 Capstone Acknowledgment

This project was developed as part of my academic **Capstone Project** under the guidance of **Dr. Hoomera Noor**.

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 🙋‍♂️ Contact

If you'd like to connect or have feedback:

- **LinkedIn**: [LinkedIn](https://linkedin.com/in/arpitamborkar)
- **Email**: arpitamborkar1@gmail.com