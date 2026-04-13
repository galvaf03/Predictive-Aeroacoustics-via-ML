# Predictive-Aeroacoustics-via-ML

## 👥 Team Members
*   Carlos Sancho Hernández
*   Guillermo Álvarez Fernández

## 📋 Project Description
This project focuses on predicting the **Scaled Sound Pressure Level (dB)** of airfoils using various Machine Learning regression models. Using the NASA Airfoil Self-Noise dataset, the system processes aerodynamic parameters (frequency, angle of attack, chord, velocity, thickness) to estimate noise levels and detect "Stall" conditions. 

The application includes a comparative analysis of 7 models (including XGBoost, Random Forest, and Neural Networks) and an **interactive dashboard** that allows real-time noise simulation and safety alerts based on diurnal/nocturnal regulations.

---

## 📖 Table of Contents


| Title | Short Description | Contributor(s) |
| :--- | :--- | :--- |
| **Data Preprocessing** | Loading UCI dataset, scaling features, and train/test splitting. | [Nombre] (100%) |
| **Model Training & Convergence** | Implementation of 7 regressors and visualization of learning curves for MLP and XGBoost. | [Nombre A] (50%), [Nombre B] (50%) |
| **Performance Evaluation** | Comparative table using R2 Score, MAE, and Mean Relative Percentage Error (MAPE). | [Nombre] (100%) |
| **Stall Classification** | Random Forest Classifier to detect aerodynamic stall conditions (Angle > 14°). | [Nombre] (100%) |
| **Interactive Dashboard** | Integrated UI using `ipywidgets` for real-time predictions and regulatory alerts. | Team |
| **Final Report / Documentation** | Summary of findings and model selection rationale. | Team |

---

## 🛠️ Requirements
To run this project, you will need the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost ipywidgets
