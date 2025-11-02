# 🌦️ Kernel Tricks for Non-Linear Data in Climate Modeling

This project focuses on developing a **climate modeling system** using **Kernel Methods** to handle **non-linear data relationships**.  
The dataset used contains **daily weather observations of Jaipur**, including temperature, pressure, humidity, and precipitation values.

## 📘 Objective
To improve prediction and visualization of non-linear climate patterns using **Kernel PCA** and **Support Vector Regression (SVR)**.

## 📊 Dataset
- **Source:** Jaipur Climate Data (open dataset)
- **Features:**
  - `date` — Observation date  
  - `meantempm`, `maxtempm`, `mintempm` — Mean, max, and min temperature  
  - `meanpressurem`, `maxpressurem`, `minpressurem` — Atmospheric pressure  
  - `maxhumidity`, `minhumidity` — Humidity range  
  - `precipm` — Precipitation in mm
  
## ⚙️ Methodology
1. **Data Cleaning:**  
   - Removed duplicates and missing values  
   - Converted date column to datetime format  
2. **Feature Scaling:**  
   - Normalized all numerical columns for kernel-based modeling  
3. **Kernel PCA:**  
   - Applied **RBF (Radial Basis Function)** kernel to capture non-linear relationships  
   - Reduced dimensionality for visualization and pattern detection  
4. **Regression Modeling (Optional):**  
   - Used **Support Vector Regression (SVR)** with RBF kernel to predict temperature trends  
5. **Visualization:**  
   - Heatmaps, scatter plots, and PCA projection plots for feature correlation and trends  

## 🧠 Technologies Used
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- scikit-learn  

## 📈 Results
- Kernel PCA successfully revealed **non-linear climatic trends** not visible in linear PCA.
- SVR provided smoother and more accurate temperature trend predictions compared to simple regression.
  
## 📂 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sdm1297/Kernal-Trick-Climate-Modeling.git
