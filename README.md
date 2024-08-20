# ML-Intern

## Project Overview
This project aims to compare various machine learning algorithms in predicting the drag coefficient of non-spherical particles using features such as Reynolds number and shape factor. Accurate prediction of drag coefficients has applications in chemical engineering, environmental science, and aerospace engineering.

## Objectives
- Implement and compare different machine learning algorithms to predict the drag coefficient of non-spherical particles using experimental data.
- Identify the most effective methods for this prediction task.

## Dimensionality of the Problem:
**Variables in Experimental Data:** 
1)Reynolds Number , 2)Shape Factor , 3)Viscosity , 4)Particle Diameter , 5)Fluid Density , 6)Particle Density.

**Input or predictor variables (u) after Feauture Importance Scores:**
1)Reynolds number (Re) 2)Shape Factor (Phi) 

## Tools & Technology Used
- **Programming Language:** Python
- **Libraries:** 
  - NumPy: For numerical computations.
  - pandas: For data manipulation and analysis.
  - matplotlib and seaborn: For data visualization.
  - scikit-learn: For implementing machine learning algorithms and optimization techniques.
- **IDE:** Google Colaboratory

## Data Preprocessing and Analysis
- **Outlier Detection:** Implemented using the Interquartile Range Method.
- **Feature Correlation:** Analyzed using correlation heatmaps.
- **Feature Importance:** Evaluated using permutation feature importance.

## Machine Learning Algorithms Implemented
- Multiple Linear Regression
- Polynomial Regression
- Support Vector Regression (SVR) with GridSearchCV
- Multiple Linear Regression with Lasso Regression
- Polynomial Regression with K-Fold Cross-Validation
- Artificial Neural Network (ANN)
- Radial Basis Function Neural Network (RBFNN)
- Random Forest Regression
- Decision Tree Regression

## Methodology
1. **Data Exploration:** Examined dataset for missing values, outliers, and feature correlations.
2. **Data Preprocessing:** Handled missing data, performed feature scaling, and detected outliers.
3. **Feature Engineering:** Assessed the importance of features to enhance model performance.
4. **Model Training and Evaluation:** Trained models using various algorithms and evaluated their performance using metrics like R² and MSE.

## Results
- **Best Performing Models:**
  - Random Forest Regression: R² = 0.9163
  - Decision Tree Regression: R² = 0.9161
  - Radial Basis Function Neural Network.
- **Visualization:** Scatter plots and log-log plots for C_d vs. Re and Actual vs. Predicted values.

## Future Work
- Incorporate advanced feature engineering techniques.
- Explore deep learning architectures for improved performance.
- Investigate the impact of different particle shape descriptors.
- Extend study to a broader range of non-spherical particle shapes and flow conditions.

## Conclusion
This study highlights the effectiveness of various machine learning algorithms in predicting the drag coefficient of non-spherical particles. RBFNN, Decision Tree Regression, and Random Forest Regression emerged as the most reliable models. Future work may involve further tuning of these models and exploring additional features to enhance prediction accuracy.

## Supervisor
Dr. Narasimha Mangadoddy  
Department of Chemical Engineering  
Indian Institute of Technology, Hyderabad



