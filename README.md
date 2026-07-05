# Climate Policy Uncertainty and Stock Return Predictability

This repository provides data, code, and supplementary materials for the paper:

**"Climate Policy Uncertainty and Regime-Dependent Stock Return Predictability"**

---

## 📌 Overview

This study examines whether climate policy uncertainty (CPU) improves short-horizon stock return predictability and whether its predictive value is regime-dependent.

We implement a unified out-of-sample forecasting framework comparing:

* ARIMAX (linear model)
* LSTM (nonlinear model)
* Hybrid (forecast combination)

---

## 📂 Repository Structure

* `data/` → Raw and processed datasets
* `code/` → All scripts for replication
* `results/` → Tables and figures
* `supplementary/` → Supplementary material

---

## ▶️ How to Replicate

1. Run data preprocessing:

```
code/01_data_preprocessing.py
```

2. Estimate models:

code/02_arimax_model.py
code/03_lstm_model.py
code/04_hybrid_model.py

3. Evaluate forecasts:

code/05_evaluation_dm_cm.py

---

## ⚠️ Data Notes

Some datasets may be subject to licensing restrictions. Users should obtain data from original sources where required.

---

## 📖 Citation

If you use this repository, please cite:

Wafi, A.S., El-Halaby, S. and Albitar, K. (2026) ‘Stock return forecasting under climate policy uncertainty: A regime-dependent model comparison’, Finance Research Letters, article 110456. https://doi.org/10.1016/j.frl.2026.110456.

---

## ✉️ Contact

Ahmed S. Wafi
Ahmed.Wafi@lmu.de 
LMU Munich University
