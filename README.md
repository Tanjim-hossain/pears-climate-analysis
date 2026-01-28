# 🌱 Climate Change Impact on Pear Production  
### Multivariate & Hierarchical Data Analysis (Ecotron Experiment)

This project investigates how future climate change interventions affect pear quality and growth using controlled Ecotron experiments in Belgium.  
It applies **multivariate methods** and **hierarchical statistical models** to analyze complex, real-world ecological data.

> 📌 Course: Multivariate and Hierarchical Data (MSc Statistics, UHasselt)  
> 📌 Team: Group 6  
> 📌 Author: Tanjim Hossain  

---

## 🔍 Research Questions

1. Which climate intervention improves pear quality compared to the “no intervention” scenario?  
2. How do climate and species affect:
   - Continuous pear quality index?
   - Binary quality outcome (good vs. poor)?
   - Longitudinal pear growth?
3. How do soil characteristics differ across climate scenarios?

---

## 🧪 Experimental Design

- **Location:** UHasselt Ecotron (Belgium)  
- **Units:** 12 Ecotron chambers  
- **Species:** Conference & Doyenne pears  
- **Scenarios (2050 projections):**
  1. No intervention (baseline)
  2. CO₂ removal
  3. Sustainable energy
  4. Sustainable transportation

Each chamber represents a replicated ecosystem with controlled climate variables.

---

## 📊 Methods

- Linear Mixed Models (hierarchical structure)
- GEE for correlated binary outcomes
- Longitudinal growth modeling
- PCA for soil feature exploration
- Bonferroni-based sample size design
- Full pipeline: EDA → Modeling → Interpretation

---

## 📈 Key Findings

- CO₂ removal and sustainable energy scenarios significantly improve pear quality.
- Baseline climate produces the *largest* pears → quality vs. size trade-off.
- Conference pears outperform Doyenne across scenarios.
- PCA shows that soil variation explains ~86% of total variance.

---

## 📄 Project Report

The full academic report describing methodology, models, and validation:

👉 [Download Project Report](./reports/Project_Report.pdf)

---

## 📂 Repository Structure

```text
data/        Raw datasets  
notebooks/  Analysis notebooks  
reports/    Generated reports and PDF


🛠 Skills Demonstrated

Multivariate statistics (PCA)

Hierarchical & longitudinal modeling

Experimental design

Statistical reporting

Real ecological data analysis
