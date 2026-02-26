# Predictive Maintenance for NASA Turbofan Engines
**Predicting Remaining Useful Life (RUL) of NASA Turbofan Engines using LSTM Deep Learning on the C-MAPSS dataset. Includes end-to-end data preprocessing, sensor trend visualization, and regression evaluation.



---

## Contents
- `Predictive_Maintenance_NASA_turbofan_clean.ipynb` — analysis and model notebook  
- `requirements.txt` — pinned dependencies (use `pip install -r requirements.txt`)  
- `scripts/` — helper scripts (`download_data.py`, `preprocess.py`, `train.py`, `evaluate.py`)  
- `models/` — saved model checkpoints (not included)  
- `data/` — (ignored) local dataset folder

---

## Key results (example)
- **RMSE:** 18.27  
- **R²:** 0.8066  
> Model trained on an NVIDIA T4 (Colab) — training time ≈ *X* minutes (single run). Include a plot of true vs predicted RUL in `results/`.

---

## Requirements
Use the provided `requirements.txt` with pinned versions:

tensorflow==2.12.0
pandas==2.1.0
numpy==1.26.0
scikit-learn==1.2.2
plotly==5.11.0
seaborn==0.12.2
kagglehub==0.3.13
