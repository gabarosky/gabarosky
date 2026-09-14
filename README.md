# Hi, I'm Gabriel 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carrizogabriel/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabarosky)

## Data Scientist & Optimization Specialist | PhD in Mathematics

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-111111?style=flat-square&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Pyomo](https://img.shields.io/badge/Pyomo-005A9C?style=flat-square&logo=python&logoColor=white)
![Gurobi](https://img.shields.io/badge/Gurobi-E00000?style=flat-square&logo=python&logoColor=white)


### Machine Learning · Statistical Inference · Business ROI · Prescriptive Analytics · MLOps

Data Scientist with a PhD in Mathematics, specializing in predictive modeling, statistical inference, and decision optimization. I transform complex algorithms into **interpretable, high-impact business tools**—bridging mathematical rigor with end-to-end deployment (MLflow, Docker, Streamlit, Power BI).

---



## 🛠️ Technical Stack & Core Competencies

* **Machine Learning & Analytics:** Predictive Modeling (Classification, Regression), Feature Engineering, Explainable AI (SHAP), Customer Analytics (Churn, CLV, Retention).
* **Experimentation & Statistics:** A/B Testing, Statistical Inference, Hypothesis Testing, Resampling Methods (Bootstrap, Permutation Tests).
* **Programming & Data Stack:** Python (Pandas, NumPy, Scikit-learn, XGBoost, SciPy), SQL, Snowflake, Power BI (DAX), Streamlit, Matplotlib/Seaborn.
* **MLOps & Workflow:** MLflow (Experiment Tracking), Docker, Git/GitHub, Conda, Pipeline Architecture.
* **Business Communication:** Data Storytelling, KPI Definition, Translating Complex Models to Non-Technical Stakeholders.
* **Optimization & Applied Mathematics:** Mathematical Programming (MILP/LP), Pyomo, Gurobi, Numerical Optimization, Linear Algebra, Ordinal Classification.

---

## 🚀 Featured Projects

### 1. 📊 [Telco Customer Churn Prediction & ROI Simulator](https://github.com/gabarosky/Telcochurn)

<p align="center">
  <img src="https://raw.githubusercontent.com/gabarosky/Telcochurn/main/docs/img/powerbi_dashboard_preview.png" width="50%" alt="Power BI Executive Simulator Preview" />
</p>

* **Problem:** High customer acquisition costs make churn prevention critical for telecom profitability. How can we predict churn and evaluate targeted retention strategies financially?
* **Solution:** Built an end-to-end ML pipeline (ROC-AUC: **0.85**, Recall: **0.82**) with **MLflow** experiment tracking and **SHAP** explainability.
* **Business Impact:** Developed an interactive **Power BI Executive Simulator**. Targeting the top 30% risk deciles projected a **$32,977 Net Benefit** with an **ROI of 0.62** (145 defections prevented).
* **Stack:** `Python` · `scikit-learn` · `XGBoost` · `SHAP` · `MLflow` · `Power BI` · `DAX`

---

### 2. ⚙️ [Predictive Analytics & Smart Insights for Garment Production](https://github.com/gabarosky/productivity_garmet_industry)


<p align="center">
  <img src="./assets/garment_app.png" width="50%" />
</p>

🚀 **[Try the interactive app live](https://performancetuner.streamlit.app/)**

* **Problem:** Manufacturing productivity fluctuates across shifts. Can we forecast shift performance tiers and isolate operational bottlenecks before work begins?
* **Solution:** Formulated an ordinal classification strategy using a `RandomForestRegressor` with Quadratic Weighted Kappa (QWK) threshold optimization, backed by **SHAP Waterfall diagnostics**.
* **Operational Impact:** Achieved a **+35.14% Accuracy Lift** and a **33.53% MAE Error Reduction** over traditional targets. Containerized with Docker and deployed as a real-time pre-shift decision tool.
* **Stack:** `Python` · `scikit-learn` · `Random Forest` · `SHAP` · `Streamlit` · `Docker`

---

### 3. 🧪 [A/B Testing: Digital Campaign Performance Analysis](https://github.com/gabarosky/AB_test)

<p align="center">
  <img src="https://raw.githubusercontent.com/gabarosky/AB_test/main/images/ab_test_results.png" width="70%" />
</p>

* **Problem:** Does a new Test ad campaign outperform the Control campaign in acquisition efficiency (Cost per Acquisition - CPA) and conversion funnel performance?
* **Solution:** Conducted paired statistical inference (**Paired Permutation Tests** & **Paired Bootstrap 95% CIs**) on 30 daily campaign observations.
* **Key Findings:** Proven statistically significant top-of-funnel engagement gains (**+3.39 pp CTR**, $p=0.0002$), while demonstrating that increased engagement did not translate into better bottom-line acquisition cost (**CPA +$0.61**, $p=0.25$).
* **Stack:** `Python` · `pandas` · `NumPy` · `Bootstrap Resampling` · `Permutation Testing` · `Matplotlib`
