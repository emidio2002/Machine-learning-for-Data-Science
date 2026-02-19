# Machine-learning-for-Data-Science

This repository showcases my final project for the *Machine Learning for Data Science* course at ENSAI (Rennes, France).  
The work is delivered as a single, self-contained Jupyter notebook that combines **theory recap**, **implementations**, and **experimental results** with an emphasis on clarity and reproducibility.

---

## Project at a glance

**Goal:** empirically validate theoretical learning results for linear regression, and implement/compare **first-order** (GD/SGD) and **zero-order** (gradient-free) optimization methods under fair evaluation budgets.

**Main components:**
- Random-design linear regression: empirical illustration of excess-risk scaling.
- Synthetic non-linear data generation and feature relevance exploration.
- Linear regression via `sklearn` and analysis of empirical risk vs sample size.
- From-scratch **Gradient Descent** and **Stochastic Gradient Descent**.
- From-scratch **Zero-order GD / Zero-order SGD** using random-direction finite differences.
- Flexible hinge-augmented model: \( f_{\beta,\gamma}(x)=x^\top\beta+(x^\top\gamma)_+ \).
- Bonus: classification on the **MAGIC Gamma Telescope** dataset with a zero-order training procedure.

---

## Repository contents
- `TP_25.pdf` — assignment statement / reference.
- `magic04.data` — bonus question dataset
- `ML_CC.ipynb` — the full notebook report (answers, code, plots, discussion).

