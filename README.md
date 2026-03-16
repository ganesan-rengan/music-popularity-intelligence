# 🎵 Music Popularity Intelligence System

## Overview
A data science project analyzing cross-platform music performance 
between Spotify and YouTube using 20,718 songs.

## Core Innovation ⭐
**Cross-Platform Gap Analysis** — classifying songs into:
- Spotify-native
- YouTube-native  
- Cross-platform hits

## Project Structure
- `data/` — raw, processed, and output datasets
- `notebooks/` — 9 phase notebooks
- `src/` — reusable Python modules
- `models/` — saved ML models
- `reports/` — figures and dashboard

## Phases
| Phase | Notebook | Description |
|-------|----------|-------------|
| 1 | 01_data_cleaning | Data cleaning & preprocessing |
| 2 | 02_eda | Sweetviz EDA report |
| 3 | 03_gap_analysis ⭐ | Cross-platform gap analysis |
| 4 | 04_feature_engineering | Feature creation |
| 5 | 05_ml_classification | RF + XGBoost classifier |
| 6 | 06_ml_regression | LR + GBM regressor |
| 7 | 07_model_evaluation | Model evaluation |
| 8 | 08_feature_importance | Insights & storytelling |
| 9 | 09_dashboard | Interactive Plotly dashboard |

## Models Used
- Random Forest · XGBoost → Classification (F1 Score)
- Linear Regression · Gradient Boosting → Regression (RMSE, R²)

## Key Results
- Gradient Boosting R² = 0.30 · RMSE = 1.41
- Gap Score identified as strongest unique feature

## Tech Stack
Python · Pandas · Scikit-learn · XGBoost · Sweetviz · Plotly