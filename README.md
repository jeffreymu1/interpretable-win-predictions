#  Position, Power, Probability: Interpreting Win Prediction in a Strategy Game

Win prediction in battle arena games is often confounded by factors like player skill and coordination. We study a battle arena-like tactical setting where combat resolves automatically, isolating the effects of team composition and unit positioning on match outcomes. We evaluate several machine learning models and find modest improvements over a majority-class baseline. We apply interpretability methods and find importances concentrated in a few unit slots and attributes, and further address directions toward recommendation-oriented modeling.

---

## Repository Structure

- `data/` — stores all raw and preprocessed data files.
- `figures/` — stores all visualizations (EDA + metrics).
- `report/` — report describing problem motivation, pipeline, methodology, and results.
- `results/` — trained models and outputs, comparisons, and artifacts.
- `src/` — jupyter notebooks used for full pipeline.

---

## Setup

Install dependencies (recommended in a virtual environment):

```bash
pip install -r requirements.txt
```

## Data Dictionary

A structured data dictionary for the final dataset lives in:

-  `data-dictionary.md`

## Key Packages

See requirements.txt for the full environment configuration. Core libraries include:

- `matplotlib`
- `numpy`
- `pandas`
- `pickle`
- `scikit-learn`
- `seaborn`
- `shap`
- `xgboost`