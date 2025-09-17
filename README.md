# Renewind-Predictive-Maintenance
Predictive maintenance for wind-turbine generators. Classification on sensor data with imbalance handling, regularisation, tuning and cost-aware thresholding to maximise early-warning recall. Feature importance guides maintenance actions.

**Commit message:** `Initial commit: EasyVisa ensemble modelling notebook and README`

---

## 6) ReneWind

```markdown
# ReneWind: Predictive Maintenance for Turbine Generators

Classify impending generator failures from sensor data to reduce downtime and maintenance cost.

## Overview
- **Goal:** Maximise early-warning recall while keeping false alarms manageable.
- **Techniques:** Upsampling/Downsampling, regularisation, hyperparameter tuning, thresholding, explainability.

## Data
Turbine sensor dataset (not included).

## How to Run
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
