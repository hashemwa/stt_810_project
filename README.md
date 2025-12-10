# STT 810 Project: Predicting Violent Crime

**Authors:** Wahid Hashem, Aryan Sharma, Zewen Wang  
**Course:** STT 810  
**Date:** December 2025

## What This Project Does

This project uses the "Communities and Crime" dataset from UCI to predict violent crime rates. We use PCA (Principal Component Analysis) to reduce 100+ features down to 3 main components, then compare Linear Regression vs Logistic Regression for prediction.

## How to Run

1. Clone this repo
2. Make sure you have Python 3.8+ with these packages:
   - pandas, numpy, matplotlib, seaborn, scikit-learn
3. Open `Analysis.ipynb` in Jupyter or VSCode/Positron
4. Run all cells from top to bottom

## Files

| File | What it is |
|------|------------|
| `Analysis.ipynb` | Main notebook |
| `crime_normalized_features.csv` | Input features (already scaled 0-1) |
| `crime_normalized_targets.csv` | Target variable (violent crime rate) |
| `communities.names` | Description of all the columns in the dataset |

## Quick Summary of Results

- We reduced 100+ features to 3 principal components
- These 3 components explain about 50% of the variance
- Both Linear and Logistic Regression achieve similar accuracy (~75%)
- Top features: urban %, race (Hispanic %), immigration/foreign-born rates, English proficiency, household size
