# Data Visualization Portfolio — Shravani Chiddarwar

**Note on Data Privacy:**  
My most substantial visualization engineering work comes from internal dashboards built for Kohl’s, Michelin Connected Fleet, and Warner Music Group. Due to confidentiality agreements, I cannot share proprietary data or internal visualizations.  
To demonstrate my skills, I have recreated *synthetic examples* that reflect the design, interactivity, and storytelling techniques from my original work.

---

## 📊 Project 1 — ETA Delay Risk Heatmap (Recreated Example)

**Tools:** Python, Tableau, Streamlit  
**Summary:**  
I built a diagnostic visualization to detect high-risk shipments for a major retail client.  
The recreated heatmap below shows the structure and patterns the real tool highlighted.

![ETA Heatmap](screenshots/eta_heatmap.png)

---

## 🎵 Project 2 — Streaming Revenue Trends (Synthetic Data)

**Tools:** Python, Snowflake, Streamlit  
**Summary:**  
At Warner Music Group, I constructed dashboards to analyze revenue patterns across DSPs, territories, and FX scenarios.  
Here is a synthetic line chart replicating the type of analysis I built.

![Streaming Trends](screenshots/stream_trends.png)

---

## 🚚 Project 3 — ETA Model Diagnostic Plot (Mockup)

**Tools:** Python, sklearn, Streamlit  
**Summary:**  
Built interactive visuals to explain ETA model deviations and contributing features to operations teams.

![ETA Diagnostic](screenshots/eta_diagnostic.png)

---

## 🧬 Project 4 — Skin Cancer Classification Model (50,000 Records)

**Tools:** R, Python, glmnet, MICE Imputation, Logistic Regression, Multinomial Regression, LASSO/Ridge, XGBoost  
**Dataset:** 50,000 patient records with 40+ clinical & demographic features  
**Goal:** Predict whether a lesion is **Benign** or **Malignant** using structured tabular data.

### 🧠 Modeling Process

**1. Data Cleaning & Preprocessing**
- Performed missing-value imputation using **MICE**, MissForest, and Mean/Mode imputation  
- Dropped features with >30% missingness; engineered clinically relevant predictors (UV exposure, sunscreen behavior, lesion size, etc.)  
- Applied standardization to numeric predictors  
- Handled high-cardinality categorical variables through grouping and frequency encoding  

**2. Feature Selection**
- Correlation analysis to remove redundant predictors  
- Univariate screening and domain-driven inclusion  
- Regularization (LASSO/Ridge) to reduce noise and improve generalization  
- Compared multiple model families:
  - Logistic Regression (full vs. reduced)
  - Multinomial Regression  
  - Penalized Regression (glmnet)  
  - XGBoost baseline  

**3. Model Training & Evaluation**
- 80/20 train-test split  
- 3-fold cross validation  
- Metrics evaluated:  
  - Accuracy  
  - Sensitivity / Specificity  
  - Confusion Matrix  
  - Precision / Recall  

**Best performance:**  
- **Training Accuracy:** ~0.6069  
- **Test Accuracy:** ~0.603 (Kaggle benchmark)  
- Balanced performance across malignant vs benign classes  
- Interpretable + stable model suitable for medical decision support  

### 📈 Visualizations (Included in PDF)
The full report includes:
- ROC curves comparing model families  
- Feature importance plots (LASSO and Ridge)  
- Confusion matrices  
- Misclassification analysis  

A synthetic preview is shown here for confidentiality, and the full process is documented in the included PDF.

### 🔍 Key Takeaways
- Built a complete ML pipeline: cleaning → imputation → feature selection → model comparison → evaluation  
- Demonstrated ability to manage **large datasets (50k rows)**  
- Focused on interpretability and diagnostic visualization  
- Combined statistical modeling with clear communication and visualization  

---

## 🧰 Skills Demonstrated
- Interactive dashboard design  
- Data storytelling & communication  
- Streamlit & Tableau development  
- Statistical & ML visualization (explainability, diagnostics)  
- Front-end thinking for visualization engineering  

---

## 🎛️ Project 5 — Streaming Engagement Dashboard (React + Node)

**Tech:** JavaScript, React, Node.js, Express, Recharts  
**Summary:**  
Built a small full-stack demo where a Node/Express API serves synthetic streaming engagement data (hours watched by genre and month), and a React frontend renders an interactive line chart and data table. This project showcases front-end visualization design, API integration, and data storytelling with a Netflix-style domain.


If you'd like access to the recreated code or additional mock dashboards, feel free to reach out!
