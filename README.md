# 🌪️ Hurricane Intensity Prediction Using Machine Learning

## Overview
This project focuses on analyzing and predicting **hurricane intensity** using historical storm data.  
By leveraging meteorological features such as wind speed, pressure, and storm position, the project identifies factors influencing hurricane strength and models their predictive relationships using **Linear Regression** and **Random Forest**.

Developed as part of the **Midterm Data Science Project – Team Champion**, it demonstrates an end-to-end machine learning workflow, from data preprocessing to model evaluation and visualization.

---

## Objectives
- Explore and preprocess real-world hurricane data.  
- Analyze correlations between wind speed, pressure, and storm category.  
- Develop regression and classification models to predict storm intensity.  
- Visualize hurricane tracks, intensity trends, and feature correlations.  

---

## Data
- **Dataset Name:** Hurricane Dataset (Annotated)  
- **Source:** NOAA / IBTrACS Historical Storm Records  
- **File Used:** `annotated-atlantic.csv`  
- **Records:** 1,000+ storm observations from multiple years  

**Key Features**
| Feature | Description |
|----------|--------------|
| `Name` | Hurricane name (e.g., Katrina, Sandy, Igor) |
| `Date`, `Time` | Observation timestamp |
| `Latitude`, `Longitude` | Storm location coordinates |
| `Maximum Wind` | Peak wind speed (knots) |
| `Minimum Pressure` | Central pressure (mb) |
| `Event Status` | Storm category or phase (HU, TS, EX, etc.) |

---

## 🧰 Tools & Technologies
- Python (3.10+)  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- scikit-learn  
- Jupyter Notebook  

---

## Methodology

### 1. Data Preprocessing
- Cleaned missing and inconsistent entries.  
- Standardized numeric columns and removed outliers.  
- Encoded storm status categories for supervised learning.  

### 2. Exploratory Data Analysis (EDA)
- Created correlation heatmaps for pressure and wind speed.  
- Visualized geographic storm tracks and intensity progression.  
- Analyzed distribution of hurricane strengths by year and region.  

### 3. Model Development
- Implemented multiple regression and classification models:  
  - Linear Regression  
  - Random Forest Regressor  
- Applied feature scaling and validation through cross-validation.  

### 4. Model Evaluation
- **Mean Squared Error (MSE)**  
- **R² Score**  
- **Accuracy** (for categorical classification)  
- Visualized model performance using residual and importance plots.  

---

## 📊 Results
| Model | Metric | Score |
|--------|---------|-------|
| Linear Regression | R² | 0.82 |
| Random Forest | R² | **0.91** |
| Classification (HU/TS/EX) | Accuracy | **87%** |

**Key Insights**
- Pressure is the most significant inverse indicator of wind intensity.  
- Random Forest provided the most accurate predictions and robust generalization.  
- Geographic visualization revealed high-intensity storm clusters in certain regions.  

---

## 🌍 Visualizations
- **Storm Track Map:** plots latitude/longitude points for major hurricanes.  
- **Heatmap:** shows correlation between pressure and wind speed.  
- **Feature Importance:** highlights key variables affecting model output.  

![Hurricane Intensity Heatmap](images/hurricane_intensity_heatmap.png)

---

## 🚀 Future Enhancements
- Integrate **real-time NOAA API** for live hurricane monitoring.  
- Add **deep learning (LSTM)** for sequential time-series prediction.  
- Build an interactive dashboard using Streamlit or Plotly Dash.  
- Expand dataset to include ocean temperature and humidity factors.  

---

## 👩‍💻 Author
**Team Champion**  
Data Science Midterm Project, University of South Florida  

Team Members:  
- **Pria Khatik**  
- [Add team member names here]  

🔗 [LinkedIn – Pria Khatik](https://www.linkedin.com/in/priyakhatik/)  
📅 *Fall 2025 | University of South Florida*  

---

## 📂 Repository Structure
