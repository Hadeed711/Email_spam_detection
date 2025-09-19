# 📧 Email Spam Detection with Machine Learning

This project is part of my internship at **DataZenix Solutions**.  
It focuses on detecting spam emails using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

---

## 🚀 Project Overview
Spam emails are a widespread problem, often containing scams, phishing content, or unwanted advertisements.  
In this project, we built an ML pipeline to classify emails as **Spam** or **Not Spam**.

---

## 🛠 Features
✔️ Text preprocessing (stopwords removal, lemmatization, cleaning)  
✔️ Model building with pipelines (Naive Bayes & RandomForest)  
✔️ Evaluation through cross-validation & visualizations  
✔️ Testing the model on unseen emails  

---

## 📊 Results
- **Accuracy**: ~97% (Naive Bayes baseline)  
- **F1 Score**: High performance across models  
- Visualized metrics with confusion matrix and classification report  

---

## 📂 Project Structure
📁 email-spam-detection
├── 📄 spam_detection.ipynb # Main Jupyter notebook
├── 📄 requirements.txt # Dependencies
├── 📄 README.md # Project documentation
└── 📂 data # Dataset (CSV file)


---

## ⚙️ Installation & Usage
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/email-spam-detection.git
   cd email-spam-detection

2. Install dependencies
   pip install -r requirements.txt 
4. Run notebook
   jupyter notebook spam_detection.ipynb
