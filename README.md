# 🚗 Used Car Price Analysis & ML Pipeline

![Python](https://img.shields.io/badge/Python-3.14.4-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.8.0-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📦 Dependencies

| Library | Version | Usage |
|---|---|---|
| `pandas` | 2.3.3 | Data loading, cleaning, manipulation |
| `numpy` | 2.3.5 | Numerical operations, IQR calculation |
| `scikit-learn` | 1.8.0 | All ML algorithms, preprocessing, metrics |
| `matplotlib` | 3.10.8 | All visualizations and plots |
| `seaborn` | 0.13.2 | Heatmaps and statistical plots |
| `joblib` | 1.5.3 | Model serialization (.pkl) |
| `jupyter_client` | 8.7.0 | Interactive notebooks |
---
## 🗂️ Project Structure

```
used_car_ml/
├── data/
│   ├── used_cars.csv            
│   └── used_cars_final.csv    
├── notebooks/
│   ├── main.ipynb
├── models/
│   ├── best_regression_model.pkl 
│   ├── kmeans_model.pkl           
│   └── scaler.pkl                
├── reports/
│   ├── .png  
│   ├── used_car_ml_report.docx 
└── README.md
```


## 📋 Dataset

**Source:** Real-world used car listings  
**Size:** 4,009 rows × 12 columns  
**Features:** Brand, Model, Year, Mileage, Fuel Type, Engine, Transmission, Exterior Color, Interior Color, Accident History, Clean Title  
**Target:** Price (USD)  
**Challenges:** String-formatted numeric columns, 6% price outliers, cascading missing values in engine/transmission