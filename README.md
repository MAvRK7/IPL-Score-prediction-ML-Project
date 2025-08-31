# 🏏 Data‑Driven Cricket: A Machine Learning Approach to IPL Score Prognostication

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)]() 
[![Framework](https://img.shields.io/badge/Framework-PyTorch%20%7C%20Scikit--Learn-orange)]() 
[![Conference](https://img.shields.io/badge/Presented%20at-ICCCNT--2025-blueviolet)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()

---

## 📌 Overview
This project presents a **machine learning‑based system** for predicting scores in Indian Premier League (IPL) matches.  
It was **presented at the 15th International Conference on Computing and Networking Technology (ICCNT)**, IIT Mandi, June 2024, and is **published on IEEE Xplore**.  
🔗 [View on IEEE Xplore](https://ieeexplore.ieee.org/document/10724464)

By leveraging **historical IPL match data** — including batting/bowling teams, runs, wickets, overs, and recent over performance — the system forecasts **total runs scored** using three different ML algorithms:
- **Linear Regression (LR)**
- **Support Vector Machine (SVM)**
- **Random Forest (RF)**

---

## 🧪 Dataset
The dataset contains **comprehensive IPL match statistics**, including:
- Match ID, date, venue
- Batting team, bowling team
- Runs, wickets, overs
- Runs & wickets in the last 5 overs
- Striker, non‑striker
- Total runs

Data was sourced from **reliable cricket databases** to ensure accuracy and credibility.

---

## ⚙️ Models Used

### **Linear Regression (LR)**
- Assumes a linear relationship between features and target (total runs).
- Produces interpretable coefficients showing feature impact.
- Best for capturing **linear dependencies**.

### **Support Vector Machine (SVM)**
- Applied in regression mode for score prediction.
- Uses kernel functions to capture **non‑linear relationships**.
- Effective in **high‑dimensional feature spaces**.

### **Random Forest (RF)**
- Ensemble of decision trees trained on random subsets of data/features.
- Captures **complex, non‑linear patterns**.
- Reduces overfitting and improves robustness.

---

## 🛠 Methodology
1. **Data Preprocessing**  
   - Removed irrelevant features, handled missing values.  
   - Selected consistently performing teams for analysis.

2. **Feature Engineering**  
   - One‑hot encoding for categorical variables.  
   - Converted date columns to datetime format.

3. **Model Training**  
   - Trained LR, RF, and SVM models on engineered features.

4. **Model Evaluation**  
   - Metrics: MAE, MSE, RMSE, R².

5. **Prediction Interface**  
   - User‑friendly functions to input match details and output predicted total runs.

---

## 📊 Key Highlights
- **End‑to‑end ML pipeline**: preprocessing → feature engineering → training → evaluation → prediction.
- **Comparative model analysis** to identify best‑performing algorithm.
- **Practical application** for sports analytics and real‑time match forecasting.

---

## 💡 Skills Demonstrated
- Data preprocessing & feature engineering
- Regression modelling (LR, SVM, RF)
- Model evaluation & performance tuning
- Python (pandas, scikit‑learn, NumPy)
- Research presentation & academic publication

---

## 📈 Potential Applications
- Real‑time IPL score forecasting
- Sports betting analytics
- Team strategy planning
- Broad applicability to other sports with structured match data

---

## 📂 Repository Structure
- `ipl_score_prediction.ipynb` — Model training & evaluation notebook  
- `ipl_dataset.csv` — Preprocessed IPL dataset  
- `utils.py` — Helper functions for preprocessing & prediction

---

📄 **Publication**:  
Presented at ICCNT 2024, IIT Mandi.  
Published on [IEEE Xplore](https://ieeexplore.ieee.org/document/10724464)
