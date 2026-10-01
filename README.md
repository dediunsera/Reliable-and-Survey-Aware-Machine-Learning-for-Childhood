# Reliable and Survey-Aware Machine Learning for Childhood Stunting

This repository contains the codebase for developing machine learning models that are both **reliable** and **survey-aware** for predicting and analyzing childhood stunting.

## 📌 Research Context
Large-scale public health surveys (like Demographic and Health Surveys) are crucial for understanding stunting. However, typical machine learning models trained on this data often ignore the complex survey design (e.g., strata, clustering, and sampling weights). Treating survey data as simple random samples can lead to biased estimates and unreliable predictions.

This project addresses this gap by developing **Survey-Aware Machine Learning** frameworks that explicitly incorporate survey design elements into the learning process.

## 🎯 Objectives
- **Survey Integration:** Adapt machine learning algorithms to respect sample weights and stratification to produce unbiased, population-level risk estimates.
- **Reliability & Calibration:** Ensure that the predicted probabilities of stunting are well-calibrated (reliable) so they can be safely used for public health interventions and resource allocation.
- **Robust Evaluation:** Provide evaluation metrics that accurately reflect performance across different demographic clusters and survey strata.

## 📂 Repository Structure
*(Structure will be populated as files are uploaded)*
- `scripts/`: Source code for survey-weighted model training, calibration, and evaluation.
- `results/`: Output metrics, calibrated probabilities, and logs.
- `figures/`: Visualizations of model calibration and survey-aware evaluations.
- `data/`: *(Private)* Confidential survey datasets used for modeling.
