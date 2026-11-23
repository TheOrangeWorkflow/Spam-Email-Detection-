# 📧 Email Spam Classification Dataset (Orange Data Mining – No-Code NLP Project)

Clean, beginner-friendly CSV datasets for building an **Email Spam Classifier (Spam vs. Not Spam)** using **Orange Data Mining** — ideal for **CBSE Class 10 & Class 12 Artificial Intelligence (Code 417 / 843) Capstone Projects**, practical files, and NLP beginners.

---

## 📂 Files Included

1. **`spam_emails.csv`** — Training dataset containing **100 balanced emails** (50 `Spam` and 50 `Not Spam`) with 2 columns: `Category` and `Message`.
2. **`test_emails.csv`** — Unseen testing dataset containing **6 brand-new emails** (`Message` column only) for live model predictions.

---

## 📥 How to Download
- Click the green **`<> Code`** button above → **`Download ZIP`**, **or**
- Click any `.csv` file → click the **Download raw file** icon at the top right.

---

## 🍊 Orange Data Mining Workflow
1. **Corpus** (`spam_emails.csv`) → **Preprocess Text** (Lowercase, Tokenization, Stopwords, Lemmatization)
2. **Preprocess Text** → **Word Cloud** & **Bag of Words** (452 word features)
3. **Bag of Words** → **Select Columns** (set `Category` as **Target**)
4. **Select Columns** → **Test and Score** (5-Fold Cross Validation) with **Naive Bayes**, **Logistic Regression**, and **Tree** → **Confusion Matrix**
5. **Live Testing:** Connect **Naive Bayes** + **Corpus (`test_emails.csv`) → Preprocess Text → Bag of Words** into **Predictions** (**6/6 accurate!**)

### 📊 Model Results (5-Fold Cross Validation)
| Model | Accuracy (CA) | F1 Score | False Positives |
| :--- | :---: | :---: | :---: |
| **Naive Bayes (Best)** | **99.0%** | **0.990** | **0** |
| **Logistic Regression** | 98.0% | 0.980 | 0 |
| **Decision Tree** | 93.0% | 0.930 | 2 |

---

## 🌐 Free Notes, Tutorials & Coaching
- **Website (Free CBSE AI, CS & IP Notes):** https://orangeworkflow.com
- **YouTube Channel (Step-by-Step Video Tutorials):** https://www.youtube.com/@TheOrangeWorkFlow
- **Created by:** Priyanka Rastogi (MCA, B.Ed — 15+ years CBSE CS & AI Educator)
