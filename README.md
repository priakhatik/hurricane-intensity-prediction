# 🌊 Atlantic Hurricane Intensity Prediction (Data Science Project)

## Overview
This project analyzes and predicts the **intensity of Atlantic hurricanes** using historical storm data.  
By leveraging meteorological variables like pressure, wind speed, and storm position, the model identifies key patterns that influence hurricane strength and evolution.  

Developed as part of the **Midterm Data Science Project – Team Champion**, this notebook demonstrates an end-to-end pipeline from data cleaning and visualization to predictive modeling.

---

## Objectives
- Explore and preprocess **Atlantic hurricane** data.  
- Analyze correlations between wind speed, pressure, and storm status.  
- Build regression and classification models to predict hurricane intensity.  
- Visualize spatial storm tracks and intensity changes over time.  

---

## Data
- **Dataset:** Annotated Atlantic Hurricane Dataset  
- **Source:** NOAA / IBTrACS historical data archive  
- **File Used:** `annotated-atlantic.csv`  
- **Records:** 1,000+ storm observations from 2004–2015  

**Key Features**
| Feature | Description |
|----------|--------------|
| `Name` | Hurricane name (e.g., Katrina, Sandy, Igor) |
| `Date`, `Time` | Timestamp of observation |
| `Latitude`, `Longitude` | Geographical storm location |
| `Maximum Wind` | Peak wind speed (knots) |
| `Minimum Pressure` | Central pressure (mb) |
| `Event Status` | Stage of the cyclone (HU, TS, EX, etc.) |

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
- Cleaned and standardized numeric columns.  
- Removed inconsistent or missing entries.  
- Encoded storm categories for supervised learning.  

### 2. Exploratory Data Analysis
- Correlation heatmaps between wind speed and pressure.  
- Geographic storm track visualizations using Plotly.  
- Distribution plots of hurricane intensities across years.  

### 3. Model Development
- Regression and classification models (Linear Regression, Random Forest).  
- Feature selection using correlation analysis.  
- Model validation using cross-validation and error metrics.  

### 4. Evaluation Metrics
- **Mean Squared Error (MSE)**  
- **R² Score**  
- **Accuracy** (for categorical models)  

---

## 📊 Results
| Model | Metric | Score |
|--------|---------|-------|
| Linear Regression | R² | 0.82 |
| Random Forest | R² | **0.91** |
| Classification (HU/TS/EX) | Accuracy | **87%** |

**Insights**
- Pressure has the strongest inverse correlation with wind intensity.  
- Certain longitudes consistently produced higher-intensity storms.  
- Random Forest delivered the best predictive performance overall.  

---

## 🌍 Visualizations
- **Hurricane Path Map:** plotted latitude and longitude points of major storms.  
- **Intensity Heatmap:** shows strong correlation between low pressure and high winds.  
- **Feature Importance Chart:** visualizes variables contributing most to predictions.  

![Sample Visualization](images/hurricane_intensity_heatmap.png)

---

## 🚀 Future Enhancements
- Integrate **real-time NOAA API** for live storm predictions.  
- Apply **deep learning (LSTM)** for temporal sequence prediction.  
- Build a **dashboard (Streamlit/Plotly Dash)** for interactive visualization.  

---

## 👩‍💻 Author
**Team Champion**  
Data Science Midterm Project, University of South Florida  

Team Members:  
- **Pria Khatik**  
- [Add other team members here]  

🔗 [LinkedIn – Pria Khatik](https://www.linkedin.com/in/priyakhatik/)  
📅 *Fall 2025 | University of South Florida*  

---

## 📂 Repository Structure
