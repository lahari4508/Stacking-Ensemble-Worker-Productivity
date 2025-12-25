# Stacking-Ensemble-Worker-Productivity
A machine learning project to predict worker productivity using ensemble models

# Worker Productivity Prediction using Stacking Ensemble ML

## 📌 Problem Statement
In the apparel industry, worker productivity plays a crucial role in meeting production targets.
Traditional evaluation methods are manual, time-consuming, and often inaccurate.
Hence, an automated and data-driven system is required to predict worker productivity efficiently.

## 💡 Proposed Solution
This project proposes a **Stacking Ensemble Machine Learning Model** to predict
garment worker productivity more accurately by combining multiple regression models.
The ensemble approach reduces individual model bias and improves overall prediction performance.

## 🧠 Models Used
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- **Stacking Ensemble (Meta-model: Linear Regression)**  

## 📊 Dataset
- Dataset: Garment Worker Productivity Dataset  
- Source: Kaggle  
- Rows: 1,197  
- Features: 15 (Targeted productivity, incentives, team size, SMV, overtime, etc.)

## 📂 Dataset Link
https://www.kaggle.com/datasets/ishadss/productivity-prediction-of-garment-employees


## ⚙️ Methodology

The proposed system uses a stacking ensemble learning approach to predict worker productivity.
Multiple base regression models are trained in parallel, and their predictions are combined
using a meta-classifier to generate the final prediction.

![Stacked Generalization Architecture](images/stacking_methodology.png)

**Figure:** Stacked generalization scheme showing base models, meta-classifier, and final prediction.

## 📈 Evaluation Metrics
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

## 🏆 Results
The stacking ensemble model outperformed individual models by achieving:
- Lower MAE, MSE, and RMSE  
- Higher R² score  
This demonstrates the effectiveness of ensemble learning in productivity prediction.

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Machine Learning  

## 🎯 Applications
- Apparel manufacturing productivity monitoring  
- Workforce performance analysis  
- Decision support for production managers  

## 👥 Team
- Lahari Arisivilli  
- M V Rajesh  
- Chonga Prasanna  
- Gonagala Hemasri  
- Vaddadi Pravallika  
- Koda Mounika  

**Pragati Engineering College – CSE (Data Science)**
