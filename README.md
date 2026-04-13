# Arjun Sahu — Data Science & ML Portfolio

**B.Tech Biotechnology · Delhi Technological University (DTU) · Batch of 2027**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-arjun--sahu-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/arjun-sahu-005193204/)
[![GitHub](https://img.shields.io/badge/GitHub-ArjunSahu123-181717?style=flat&logo=github)](https://github.com/ArjunSahu123)
[![Email](https://img.shields.io/badge/Email-Sahu1305jhs%40gmail.com-D14836?style=flat&logo=gmail)](mailto:Sahu1305jhs@gmail.com)

---

## About

I'm a third-year Biotechnology student at DTU who started building data science projects in my first year and hasn't stopped since.

My background is a little unusual — most people doing ML come from CS or Statistics. I come from Biotechnology, which taught me something that doesn't show up in textbooks: real data is messy and full of exceptions, just like biological systems. You don't force a model onto data. You understand what the data is trying to say first.

I work across the full data stack — exploratory analysis, machine learning, and BI dashboards. My toolkit includes Python, SQL, Scikit-learn, XGBoost, SHAP, Power BI, and Streamlit.

I'm actively looking for **Data Analyst / Data Science / ML internships for Summer 2025** — open to any industry, remote or Delhi-based.

---

## Projects

### Breast Cancer Classification
*Binary classification on medical biopsy data — where my Biotechnology background directly informs the analysis.*

The Wisconsin Diagnostic dataset has 569 biopsy samples and 30 nuclear features. Before touching any model, I ran correlation analysis to understand which features actually mattered. Concave points, nuclear perimeter, and area turned out to be the strongest signals for malignancy.

| Metric | Result |
|--------|--------|
| Dataset | 569 FNA biopsy samples, 30 features |
| Test Accuracy | **94.15%** |
| 7-Fold CV Accuracy | **94.20%** (range: 90.1% – 97.5%) |
| Models compared | Decision Tree · Logistic Regression |

The cross-validation range tells the real story here — the model is consistent, not just lucky on a single test split. EDA before modelling made all the difference.

**Tools:** Python · Scikit-learn · Pandas · Seaborn · Cross-Validation

[![Code](https://img.shields.io/badge/View%20Code-GitHub-181717?style=flat&logo=github)](https://github.com/ArjunSahu123/Breast-cancer-prediction)

---

### Belarus Car Price Prediction
*Regression on a 56,000-row real-world marketplace dataset. The most interesting part wasn't the model — it was what the data revealed.*

Started with 56,244 records of used cars from a Belarusian marketplace. After cleaning (IQR + Z-score outlier removal), 53,157 records remained. The real engineering challenge was the brand column — 96 car brands with highly uneven representation. I grouped them into 7 regional segments to reduce cardinality without losing signal.

| Metric | Result |
|--------|--------|
| Dataset | 56,244 rows (cleaned to 53,157) |
| Model | Decision Tree Regressor |
| R² | **0.73** |
| MAE | **$2,090** |
| GridSearchCV combinations | 384 (5-fold CV) |
| Top predictor | Year of manufacture — **30% of variance** |

Manufacture year explains more price variance than mileage (21%) or transmission (28%). That finding is counterintuitive and genuinely useful for anyone doing pricing analysis.

**Tools:** Python · Scikit-learn · Pandas · GridSearchCV · Feature Engineering

[![Code](https://img.shields.io/badge/View%20Code-GitHub-181717?style=flat&logo=github)](https://github.com/ArjunSahu123/Belarus-Car-Price-Prediction)

---

### Business Sales Dashboard & Insights
*End-to-end analytics pipeline — from raw SQL data to Power BI dashboard with a forecasting layer.*

Built a complete SQL → Python ETL → Power BI pipeline for sales analytics. The goal wasn't to make it look good — it was to build something a non-technical manager could open on a Monday morning and immediately know where to focus.

| What I built | Details |
|-------------|---------|
| KPI dashboards | 12+ interactive visualisations |
| Coverage | Revenue growth · Product performance · Regional profitability |
| Forecasting | Linear regression for monthly sales estimation |
| Outcome | Automated monthly reporting, eliminated manual tracking |

**Tools:** Power BI · DAX · SQL · Python · Pandas · ETL · Linear Regression

---

### Cardiovascular Disease Prediction
*Healthcare classification using patient clinical records.*

Trained and benchmarked multiple classification models on cardiovascular patient data. Chose evaluation metrics based on what actually matters in a medical context — false negatives cost more than false positives here, so accuracy alone was never the target.

| Models tested | Logistic Regression · Decision Tree · Random Forest |
|--------------|---------------------------------------------------|
| Key focus | Clinically meaningful metric selection, EDA on clinical features |

**Tools:** Python · Scikit-learn · Pandas · Matplotlib · Seaborn

[![Code](https://img.shields.io/badge/View%20Code-GitHub-181717?style=flat&logo=github)](https://github.com/ArjunSahu123/Cardiovascular-Disease-Prediction)

---

## Skills

**Languages & Libraries**
Python · SQL · Java · C · C++

**ML & AI**
Scikit-learn · XGBoost · LightGBM · TensorFlow · SHAP · NLTK · OpenCV

**Data & Analytics**
Pandas · NumPy · SciPy · EDA · Feature Engineering · ETL · Cross-Validation · Hyperparameter Tuning

**BI & Visualisation**
Power BI (DAX) · Tableau · Matplotlib · Seaborn · Plotly · Excel

**Developer Tools**
Git · GitHub · Streamlit · Jupyter · VS Code · REST APIs · N8N · Make

---

## Certifications

| Certification | Issuer | Year |
|--------------|--------|------|
| Product Management Basics | Pendo.io | 2025 |
| Data Science Professional Certificate | GeeksforGeeks × IBM | 2024 |

---

## Education

| Institution | Degree / Board | Grade | Year |
|-------------|---------------|-------|------|
| Delhi Technological University (DTU) | B.Tech — Biotechnology | **8.3 CGPA** | 2023–2027 |
| Sanskar Public School, Gwalior | CBSE — Class XII | **85%** | 2022 |
| Rani Laxmibai Public School, Jhansi | ICSE — Class X | **96%** | 2020 |

---

## A Few Other Things

**Ranked 8th nationally at Eureka Junior 2021** (E-Cell IIT Bombay) — pitched a startup idea to a jury at IIT Bombay at age 16, out of 1,000+ applicants.

**Co-Head of Corporate Sponsorship at E-Cell DTU** — managing the full sponsorship pipeline for E-Summit, which draws 100,000+ footfall annually.

**AI Data Trainer at Outlier.ai** — evaluating Hindi-language AI model outputs, contributing to ~20% improvement in model accuracy.

Active poet for 3+ years. State-level chess player.

---

## Contact

**Email:** Sahu1305jhs@gmail.com
**LinkedIn:** [linkedin.com/in/arjun-sahu](https://www.linkedin.com/in/arjun-sahu-005193204/)
**Location:** New Delhi · Open to remote

> *"You don't force a model onto data. You understand what the data is trying to say first."*
