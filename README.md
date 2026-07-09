# ML Algorithms From Scratch & Comparative Analysis

Implementation and side-by-side benchmarking of core machine learning algorithms on standard datasets — built to deeply understand the math and assumptions behind each model, not just call a library function.

## Why this repo exists
Most ML tutorials show you *how* to call `.fit()`. This repo focuses on *why* each algorithm behaves the way it does — bias/variance tradeoffs, decision boundaries, and where each one breaks down — through direct implementation and comparison.

## Algorithms covered
| Algorithm | Type | Notebook |
|---|---|---|
| Linear Regression | Regression | `01_linear_regression.ipynb` |
| Logistic Regression | Classification | `02_logistic_regression.ipynb` |
| Decision Trees | Classification | `03_decision_trees.ipynb` |
| Random Forest | Classification | `04_random_forest.ipynb` |
| SVM | Classification | `05_svm.ipynb` |
| KNN & Naive Bayes | Classification | `06_knn_naive_bayes.ipynb` |


## Tech Stack
Python · scikit-learn · pandas · NumPy · Matplotlib · Seaborn

## Project Structure
```
ml-algorithms-from-scratch/
├── notebooks/       # one notebook per algorithm & EDA
```

## How to Run
```bash
git clone https://github.com/bilaltariq221744-png/ml-algorithms-from-scratch.git
cd ml-algorithms-from-scratch
pip install -r requirements.txt
jupyter notebook notebooks/01_linear_regression.ipynb
```

## Key Learnings
- Bias-variance tradeoff observed directly by comparing linear models vs. ensemble methods
- Feature scaling's impact on distance-based models (KNN, SVM) vs. tree-based models
- Decision boundary visualization to understand model behavior beyond raw accuracy

## Author
**Bilal Tariq** — Final Year Mechatronics Engineering | Founder & CTO, Embotics

