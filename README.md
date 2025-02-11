# Boston Housing Price Prediction Using Machine Learning
## Project Overview
This project aims to predict housing prices in the Boston area using various machine-learning models. The solution provides valuable insights for real estate valuation and investment strategies.

## Objective
The primary goal is to build an accurate machine learning model to predict housing prices based on multiple features such as the number of rooms, location, and structural attributes.

## Dataset Description
The dataset used for this project was sourced from the OpenML house prices dataset. It contains X rows and Y features, including information about property characteristics and sale prices.
Key columns include:
- LotArea: Size of the lot in square feet
- OverallQual: Overall material and finish quality
- YearBuilt: Year when the house was built
- SalePrice: Sale price of the house (target variable)

## Data Preprocessing
Data preprocessing was a crucial step to clean and transform the raw data for machine learning. Key steps included:
1. Handling Missing Values: Filled or removed missing entries using imputation techniques.
2. Normalization: Applied normalization to ensure all features had a similar scale.
3. Encoding Categorical Variables: Used Label Encoding for categorical variables such as `Street`, `KitchenQual`, and `ExterCond`.
4.  Outlier Removal: Removed extreme values to improve model performance.

## Feature Engineering and Encoding
Categorical columns were encoded using `LabelEncoder` to ensure compatibility with machine-learning models. Boolean columns were converted to integer types.


## Model Selection and Training
Several machine learning models were tested:
- Linear Regression: Used as a baseline model, yielding an MSE of 1.5982e+17.
- Random Forest: Achieved an improved MSE of 0.1043.
- Gradient Boosting: Selected as the final model, providing an excellent MSE of 0.0768.
Training was performed on 80% of the data, with the remaining 20% used for validation.

## Evaluation Metrics
The following metrics were used to assess model performance:
- Mean Squared Error (MSE)
The Gradient Boosting model outperformed other models in terms of both accuracy and error metrics.

## Results and Analysis
- The Gradient Boosting model achieved the lowest MSE, making it the best choice for this dataset.
- Proper feature engineering and normalization significantly improved model accuracy.
- Challenges such as missing data and imbalanced distributions were successfully addressed.

## Challenges and Solutions
1. Data Imbalance: Addressed by normalization and feature engineering.
2. High MSE in Linear Regression: Resolved by selecting a more robust model (Gradient Boosting).
3. Categorical Encoding: Careful handling of object-type columns using Label Encoding.

## Tools and Libraries Used
- Programming Language: Python
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `GradientBoosting`
  - `Conda environment for package management`

## Conclusion and Insights
This project demonstrated the importance of data preprocessing and model selection in predictive analytics. The Gradient Boosting model was particularly effective for this dataset, achieving high accuracy and minimal error.
Key Takeaways:
- Gradient Boosting outperformed traditional models like Linear Regression.
- Proper preprocessing and encoding are critical for high-performance machine learning.



## Contact Information
Feel free to connect or reach out:

GitHub Repository: https://github.com/leonardo0231 

LinkedIn Profile: linkedin.com/in/jalil-ahmad-afshar-055a98186

Email: jalilahmad1309@gmail.com

Telegram: t.me/jalilov051
