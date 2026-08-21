# Hi, I'm Zulfan Zidni Ilhama
Data Scientist | Machine Learnnig | Analytics

Introduction

You can contact me through:  
Email: [zulfanzidni@gmail.com](mailto:zulfanzidni@gmail.com)  
LinkedIn: [zulfanzidni](www.linkedin.com/in/zulfanzidni)

## [Diamond Price Prediction](https://github.com/zulfanzidni/Portfolio_Repository/tree/d9861574aa4b6c254895508b3faf64cfa068b4b0/Diamond%20Price%20Prediction)

### Project Description
This project aims to predict the price of diamonds based on their physical characteristics (such as carat, cut, color, clarity, depth, table, and dimensions x, y, z). By utilising various machine learning regression models, this project demonstrates the process of data preprocessing, model training, and evaluation to find the most accurate model for price prediction.

### Tech Stack & Skills
**Machine Learning Models**:  
Linear Regression, Decision Tree Regressor, Random Forest Regressor, K-Nearest Neighbors (KNN) Regressor, XGBoost Regressor, Ridge Regression
  
 **Data Processing Techniques**: Handling Unreasonable Data (dropping 0 dimensions), Label Encoding, Feature Scaling (StandardScaler)

### Results
The models were evaluated using multiple metrics including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score. **The Best model is Random Forest**.

| Model | MAE | MSE | RMSE | R² Score |
|-------|-----|-----|------|----------|
| **Random Forest** | 264.9220 | 272603.15 | 522.1141 | **0.9827** |
| XGBoost | 275.9199 | 290818.63 | 539.2760 | 0.9815 |
| Decision Tree | 354.2690 | 535477.94 | 731.7636 | 0.9660 |
| KNeighbors | 405.4477 | 638317.12 | 798.9475 | 0.9594 |
| Linear Regression| 848.4154 | 1762425.25| 1327.5637| 0.8880 |
| Ridge | 848.5121 | 1762149.56| 1327.4598| 0.8880 |
