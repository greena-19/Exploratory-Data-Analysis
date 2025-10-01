# Exploratory Data Analysis (Titanic – Synthetic)

This repository contains:
- `titanic_train_synthetic.csv` – a Titanic-like dataset (800 rows) for practice.
- `EDA_.ipynb` – a ready-to-run EDA notebook with plots and observations.
- `EDA_Report.pdf` – a 1–2 page PDF summarizing approach and findings.

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn notebook
   ```
2. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook EDA_Titanic_Task5.ipynb
   ```

## Notebook Outline
- **Overview:** `.info()`, `.describe()`, missing values
- **Univariate:** histograms, boxplots, category counts
- **Bivariate:** survival rates by `Sex`, `Pclass`, `Embarked`
- **Multivariate:** correlation heatmap, pairplot (subset)
- **Observations:** concise write-up for each section

## Notes
- The dataset is synthetic but mimics real Titanic structure and broad patterns (e.g., higher survival for females and 1st class).
- For deeper analysis, consider feature engineering (e.g., `FamilySize = SibSp + Parch + 1`, titles from names) and simple models.

---
Generated on: 2025-10-01 20:40:41
