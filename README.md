# exoplanet_detection_methods_accuracy

# Evaluating Accuracy of Exoplanet Detection Methods

This project analyzes data from the NASA Exoplanet Archive to answer the question:  
**"Which exoplanet detection method yields the most consistent measurements for each orbital parameter?"**

## 🔍 Research Summary

Detection methods such as Radial Velocity, Transit, Microlensing, and Imaging yield multiple orbital parameters across confirmed exoplanets. This project:

- Aggregates measurements from different researchers for each exoplanet
- Calculates standard deviations and standard error of key orbital parameters per detection method
- Normalizes accuracy metrics for sample size and method representation
- Visualizes method-wise reliability across semi-major axis, eccentricity, inclination, and more
- Classifies reliability metrics (standard deviation, standard error) into reliability categories using KMeans vs non-Machine Learning Classification Schemes
- Implements RandomForestClassifiers to predict reliability categorization and compare unsupervised classification schemes from supervised learning metrics  

## 📊 Tools & Skills Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Exploratory Data Analysis (EDA)
- Uncertainty Quantification & Error Propagation
- Scientific Visualization
- Data Normalization & Statistical Aggregation
- Unsupervised Data Classification using Machine Learning (K-Means) vs non-Machine Learning approaches
- Data Prediction and Performance Quantification using RandomForestClassifiers 

## 📁 Project Layout

See the `/notebooks` folder for step-by-step analysis.

## 🔗 Data Source

- NASA Exoplanet Archive: https://exoplanetarchive.ipac.caltech.edu/

