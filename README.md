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
| **0. Data Search and Objectives** | Search of reliable sources that offer interesting data for a ML project. | Team |
| **1. Data Loading** | Retrieval of the NASA Airfoil Self-Noise dataset from the UCI Machine Learning Repository. | Carlos (60%) <br> Guillermo (40%) |
| **2. Preprocessing** | Feature engineering for stall detection, data scaling, and splitting into training/testing sets. | Carlos (60%) <br> Guillermo (40%) |
| **3. Model Benchmarking** | Definition of 7 regression algorithms (XGBoost, MLP, Random Forest, etc.) for performance comparison. | Team |
| **4. Training Models and Convergence** | Model fitting and visualization of learning curves to monitor error reduction over iterations. | Team |
| **5. Safety and Deployment** | Implementation of the prediction logic, including regulatory noise limits and stall alert systems. | Carlos (40%) <br> Guillermo (60%)  |
| **6. Output** | Interactive dashboard using `ipywidgets` for real-time flight analysis and visual comparison of results. | Carlos (40%) <br> Guillermo (60%) |
| **7. Presentation** | Design of support slides to illustrate the objectives, elaboration and results of the project. | Carlos (100%) |
| **8. Documentation** | Creation of a Github repository to make the code and information available. | Guillermo (100%) |

---

## 🛠️ Requirements
To run this project, you will need the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost ipywidgets
