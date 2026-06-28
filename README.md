# Fake-Job-Posting-Detection
# 🛡️ Fake Job Posting Detection

An AI/ML project that detects fraudulent job postings using Machine Learning. The model analyzes job descriptions and predicts whether a job posting is **Real** or **Fake**, helping job seekers avoid online recruitment scams.

---

## 📌 Project Overview

Fake job advertisements have become increasingly common on online job portals. This project uses Machine Learning techniques to classify job postings as **Real** or **Fake** based on textual and categorical features.

The project includes:
- Data preprocessing
- Feature engineering
- Text vectorization using TF-IDF
- Model training
- Performance evaluation
- Prediction on new job postings

---

## 🎯 Objectives

- Detect fake job advertisements automatically.
- Reduce online job fraud.
- Build an accurate and efficient ML classification model.
- Compare different machine learning algorithms.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

## 📂 Dataset

Dataset Source:
- Fake Job Postings Dataset (Kaggle)

Typical Features:
- title
- company_profile
- description
- requirements
- benefits
- employment_type
- required_experience
- required_education
- industry
- function
- fraudulent (Target)

Target Variable:
- 0 → Real Job
- 1 → Fake Job

---

## 📊 Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Handle Missing Values
4. Text Preprocessing
5. TF-IDF Vectorization
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Save Model
10. Predict New Job Posts

---

## 🤖 Algorithms Used

- Logistic Regression
- Naive Bayes
- Random Forest
- Decision Tree

Recommended Model:
- Logistic Regression (Fast and Accurate)

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📁 Project Structure

```
Fake-Job-Posting-Detection/
│
├── dataset/
│   └── fake_job_postings.csv
│
├── notebooks/
│   └── Fake_Job_Posting_Detection.ipynb
│
├── models/
│   └── fake_job_detector.pkl
│
├── images/
│   ├── confusion_matrix.png
│   └── accuracy_graph.png
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Fake-Job-Posting-Detection.git
```

Move into the project folder

```bash
cd Fake-Job-Posting-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

Or run the application

```bash
python app.py
```

---

## 📊 Sample Prediction

Input:

```
Title:
Data Scientist

Description:
Looking for an experienced Data Scientist with Python,
Machine Learning, SQL, and communication skills.

Requirements:
Bachelor's Degree
2+ years experience
```

Output

```
Prediction:
✅ Real Job Posting
```

---

## 📸 Results

Example Model Accuracy:

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 96% |
| Naive Bayes | 94% |
| Decision Tree | 91% |
| Random Forest | 95% |

*(Accuracy may vary depending on dataset and preprocessing.)*

---

## 💡 Future Improvements

- Deploy using Flask or Streamlit
- Deep Learning (LSTM/BERT)
- Real-time job URL scanning
- Browser Extension
- Explainable AI (SHAP)

---

## 📦 Requirements

```
Python >= 3.10
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib
jupyter
```

Install using

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Shiwank Sharma**

B.Tech CSE (AI)

Rungta College of Engineering and Technology

Email: shiwanksharma236@gmail.com

---

## ⭐ If you found this project useful

Give this repository a ⭐ on GitHub.
