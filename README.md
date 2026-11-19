# 🧠 Fake Review Detection using NLP and Hybrid Machine Learning

## 📌 Project Overview

This project aims to address a real-world problem in e-commerce: **fake review detection**.  
Fake reviews can mislead consumers, damage platform trust, and create unfair competition among sellers.

To tackle this problem, we propose a **hybrid machine learning framework** that integrates:

- Review behavioral features  
- Linguistic (NLP-derived) features  
- Product and seller contextual information  

Unlike traditional approaches that rely on a single type of feature, our method combines multiple signals to improve detection performance.

---

## 🎯 Objectives

- Identify fake reviews using machine learning models  
- Compare different feature types:
  - Baseline (metadata)
  - Linguistic (NLP-based features)
  - Hybrid (combined features)
- Evaluate the effectiveness of feature fusion in improving classification performance  

---

## 📂 Dataset

We use a large-scale synthetic e-commerce dataset containing:

- 100,000+ customer reviews  
- Review metadata (ratings, helpful votes, etc.)  
- Linguistic features (sentiment, subjectivity, polarity, emotion)  
- Product information  
- Seller information  

### Key Files

- `reviews.csv` — core review-level data  
- `sentiment_labels.csv` — NLP-derived features  
- `products.csv` — product-level metadata  
- `sellers.csv` — seller-level metadata  

---

## ⚙️ Project Workflow

The project follows a structured pipeline:

### Phase 1 — Data Preparation
- Merge multiple datasets into a unified dataset  
- Clean missing values and inconsistencies  

### Phase 2 — Exploratory Data Analysis (EDA)
- Analyze distributions of key variables  
- Compare fake vs genuine review patterns  

### Phase 3 — Model Development

#### 1. Baseline Model
- Uses review metadata only  
- Example features:
  - review length  
  - helpful ratio  
  - verified purchase  

#### 2. Linguistic Model
- Uses NLP-derived features  
- Example features:
  - sentiment score  
  - subjectivity  
  - polarity  
  - emotion  

#### 3. Hybrid Model (Main Contribution)
- Combines:
  - metadata features  
  - linguistic features  
  - product & seller context  

---

## 🧪 Models

We experiment with multiple models, including:

- Logistic Regression  
- Random Forest  
- (Optional) Gradient Boosting / XGBoost  

All models are evaluated under the same conditions for fair comparison.

---

## 📊 Evaluation Metrics

We evaluate model performance using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 📈 Expected Contributions

- Demonstrate that **hybrid feature integration improves performance**  
- Provide insights into:
  - behavioral patterns of fake reviews  
  - linguistic characteristics of deceptive content  

---

## 🧠 Key Insight

Fake reviews cannot be reliably detected using a single signal.  
Our results show that combining:

> **behavior + language + context**

leads to more robust and accurate detection.

---

## 🛠️ Tools & Environment

- Python  
- Pandas / NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Google Colab / Kaggle Notebooks  

---

## 📁 Repository Structure


Our project has data/, notebooks/, src/, results/, report/ and README.md as components


---

## 👥 Team Contributions

| Member | Contribution |
|------|-------------|
| A (Leader) | Hybrid model, integration, report writing |
| B | Data preprocessing, baseline model |
| C | Linguistic model, theoretical analysis |
| D | Evaluation, visualization, presentation |

---

## 🔗 Notes

- Due to dataset size, full data is not uploaded to GitHub  
- Code is provided via notebooks  
- Results and figures are included in `/results`  

---

## 📌 Conclusion

This project demonstrates that combining NLP-based features with structured data provides a more effective approach to fake review detection compared to single-source methods.

---


## Repository note

This private copy is retained for portfolio access. It is a collaborative group project; see the original repository for project history and shared contributions: https://github.com/Zijian211/42850NLPA3GROUP76.

The source datasets and generated output files are not included here. Use the data files described above from the original project before running the notebooks.
