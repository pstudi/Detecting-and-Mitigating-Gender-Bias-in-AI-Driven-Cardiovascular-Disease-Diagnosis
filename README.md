# Detecting and Mitigating Gender Bias in AI-Driven Cardiovascular-Disease-Diagnosis 🫀🩺
This project involves the technical implementation of a Master's Thesis that focuses on identifying and reducing gender bias in cardiovascular disease predictions through Machine Learning (ML). It encompasses model training, bias detection with FairMLHealth and Fairlearn, and the application of bias mitigation techniques with Fairlearn and AIF360.

---

## 🎯 **Project Goals**

* Profile gender balance across CVD datasets; standardize preprocessing and fixed train/test splits.
* Train baseline models (KNN, Decision Tree, Random Forest, MLP) with controlled gender-ratio scenarios (75/25, 25/75, 50/50).
* Quantify fairness with DPD/SPD, EqOpp/EqOdds, DIR, plus group TPR/FPR.
* Apply mitigation: Fairlearn reductions/Threshold Optimizer and AIF360 Reweighing/Equalized Odds.
* Compare fairness–performance trade-offs across datasets and models.

## ❓ Research Questions

Main RQ: How can gender bias in AI-based diagnosis of cardiovascular disease be effectively detected and mitigated in the healthcare sector?

* RQ1: How can gender bias in cardiovascular disease be identified and addressed?
* RQ2: How does using gender bias detection and mitigation strategies in AI-based cardiovascular disease diagnosis affect model performance and fairness?

---

## 📂 Project Structure

data/: contains the datasets used and their corresponding links to download them
notebooks/: contains data processing, descriptive statistics, modeling, fairness evaluation and mitigation notebooks
requirements: packages needed to run the notebooks
License: open-source license for usage and citation
README.md: this file

---

## Datasets

- Kaggle CVD: A public dataset of ~70,000 patients with 12 clinical variables used to model CVD risk and analyze gender-related disparities 
- Mendeley CVD: An anonymized hospital cohort (~1,000 patients, India) with ~14 columns
- Composite Heart Failure: A compiled set based on five UCI heart datasets (Cleveland, Hungarian, Statlog, Long Beach VA, Switzerland), ~918 instances with 11 clinical features

---

## 🧠 Objectives

- Build machine learning models to predict CVD using medical datasets.
- Evaluate fairness with respect to gender as a sensitive attribute.
- Apply post-processing and in-processing bias mitigation techniques.
- Compare model accuracy and fairness trade-offs.

---

## 🛠️ Tools and Libraries

- Virtual Environment (Python 3.10.18) 
- Python 3.11.9
- Scikit-learn
- Fairlearn
- AIF360
- Pandas, NumPy, Matplotlib, Seaborn

---

## 📊 Models Used

- K-Nearest Neighbors (KNN)
- Decision Tree (DT)
- Random Forest (RF)
- MLP (Multilayer Perceptron)

---

## ⚖️ Fairness Evaluation

Metrics: Demographic/Statistical Parity Difference (DPD/SPD), Disparate Impact Ratio (DIR), Equality of Opportunity Difference (TPR gap), Equalized Odds Difference (TPR/FPR gaps), plus group TPR/FPR/precision/recall for context.

- **Toolkits**:
  - [Fairlearn](https://github.com/fairlearn/fairlearn)
  - [FairMLHealth](https://github.com/KenSciResearch/fairMLHealth)
  - [AIF360](http://aif360.readthedocs.io/en/stable/#)
  

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cvd-gender-bias.git
   cd cvd-gender-bias
