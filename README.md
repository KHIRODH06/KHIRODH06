<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=22D3F7&center=true&vCenter=true&width=435&lines=Khirodh+Chandra+Mohapatra;Data+Science+%7C+Credit+Risk+%7C+BI;Python+%7C+SQL+%7C+Power+BI+%7C+Tableau;Machine+Learning+%7C+Risk+Modeling" alt="Typing Header" />
</div>

---

## 👨‍💻 **About Me**
I'm a **passionate data professional** specializing in **credit risk analytics** and **business intelligence**. With expertise in building predictive models and interactive dashboards, I bridge the gap between technical analysis and business decision-making.

🔭 **Currently Working On:** IFRS 9 compliant ECL models<br>
🌱 **Currently Learning:** Deep learning for risk prediction<br>
💬 **Ask Me About:** PD/LGD modeling, BI dashboards, Python automation<br>
⚡ **Fun Fact:** I analyze credit risk by day and cricket statistics by night

---

## 🛠 **Technical Stack**

### 📚 **Languages & Frameworks**
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white&style=for-the-badge">
  <img alt="SAS" src="https://img.shields.io/badge/SAS-FF9E0F?logo=sas&logoColor=white&style=for-the-badge">
  <img alt="Excel" src="https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white&style=for-the-badge">
</p>

### 📊 **Data Science & ML**
<p>
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style=for-the-badge">
  <img alt="Scikit-Learn" src="https://img.shields.io/badge/Scikit_Learn-F7931E?logo=scikit-learn&logoColor=white&style=for-the-badge">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=for-the-badge">
  <img alt="XGBoost" src="https://img.shields.io/badge/XGBoost-3776AB?logo=xgboost&logoColor=white&style=for-the-badge">
</p>

### 📈 **Visualization & BI**
<p>
  <img alt="Power BI" src="https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black&style=for-the-badge">
  <img alt="Tableau" src="https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white&style=for-the-badge">
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-11557C?logo=python&logoColor=white&style=for-the-badge">
  <img alt="Plotly" src="https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white&style=for-the-badge">
</p>

### 🏦 **Credit Risk Specialization**
- Probability of Default (PD) Modeling
- Loss Given Default (LGD) Estimation
- Exposure at Default (EAD) Calculation
- IFRS 9 Expected Credit Loss (ECL)
- Basel III/IV Compliance

---

## 🚀 **Featured Projects**

### 1. [Credit Risk Scorecard Model](https://github.com/KHIRODH06)
**Tech:** Python, XGBoost, SHAP, SQL  
**Impact:**
- Achieved 92% AUC in default prediction
- Reduced manual review time by 35%
- Identified 25% more high-risk accounts

```python
# Model training snippet
from xgboost import XGBClassifier
from sklearn.metrics import roc_auc_score

model = XGBClassifier()
model.fit(X_train, y_train)
probabilities = model.predict_proba(X_test)[:, 1]
print(f"AUC Score: {roc_auc_score(y_test, probabilities):.2f}")
