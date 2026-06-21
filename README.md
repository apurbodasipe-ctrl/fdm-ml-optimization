# Machine Learning-Driven Multi-Objective Optimisation of FDM 3D Printing

## Overview
This project presents a data-driven framework to optimise FDM 3D printing parameters using Machine Learning and NSGA-II optimisation.
Developed a data-driven framework to optimise FDM 3D printing process parameters using Machine Learning and Multi-Objective Optimisation.

Generated a physics-informed simulation dataset (1000 samples) with 7 process parameters and 4 performance metrics (warpage, build time, energy consumption, quality index)

Built predictive models using Random Forest and XGBoost, achieving high accuracy:

* Warpage (R² ≈ 0.93)
* Build Time (R² ≈ 0.97)
* Energy (R² ≈ 0.86)
* Quality (R² ≈ 0.97)

Implemented NSGA-II (Non-dominated Sorting Genetic Algorithm II) for multi-objective optimisation to identify Pareto-optimal solutions, balancing:

* Warpage minimisation
* Build time reduction
* Energy efficiency
* Quality maximisation

Conducted SHAP-based explainability analysis to interpret model behaviour, revealing the dominant influence of geometric parameters such as raster angle, layer height, and infill density

Extracted extreme optimal solutions (best for each objective) and performed trade-off analysis for decision-making

Outcome: Developed a scalable and intelligent optimisation framework for sustainable additive manufacturing.
## Objectives
- Minimise warpage
- Reduce build time
- Reduce energy consumption
- Maximise print quality

## Results

### Pareto Front
![Pareto](pareto_front.png)

### Model Prediction
![Prediction](actual_vs_predicted_warpage.png)

### SHAP Analysis
![SHAP](shap_summary_warpage.png)

