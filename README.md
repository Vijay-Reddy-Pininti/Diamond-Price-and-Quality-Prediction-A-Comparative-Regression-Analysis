# Diamond Price and Quality Prediction: A Comparative Regression Analysis


<!-- MOTIVATION -->
## Motivation



The motivation behind this project stems from the desire to leverage advanced statistical methods and machine learning techniques to tackle the complex challenge of accurately predicting diamond prices. By introducing a novel feature, 'quality', and employing a range of regression models and hyperparameter optimization, the project aims to not only enhance predictive accuracy but also provide deeper insights into the factors influencing diamond valuation, thereby contributing valuable knowledge to the field of gemology and economics.


<!-- ABOUT THE PROJECT -->
## Introduction

This project aims to predict diamond prices using Linear and Ridge Regression models, providing insights into factors influencing diamond valuation. The use of Mean Squared Error (MSE) allows for precise evaluation of model performance. Additionally, the project tackles class imbalances using the Synthetic Minority Over-sampling Technique (SMOTE), ensuring robust and reliable predictions.


<p align="right">(<a href="#top">back to top</a>)</p>

## Built With

Here are the awesome tools we used:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0081C8?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![imbalanced-learn](https://img.shields.io/badge/imbalanced--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)


<p align="right">(<a href="#top">back to top</a>)</p>


## Datasets

The dataset contains information about diamonds. The dataset contains 53940  rows and 13 columns. Based on our analysis, the dataset contains columns like <b>carat, cut, color, clarity, average US salary, depth and many other relevant features.</b> <br><br>
Furthermore, we introduced a novel feature <b> quality </b> to predict the quality of diamond.

## Feature Engineering
- **New Feature**: 'Quality' of diamonds, predicted using Logistic Regression.
- Emphasis on data preprocessing and feature selection to enhance model accuracy.

## Key Results
- Achieved a significant reduction in MSE, indicating high model precision.
- The Logistic Regression model effectively classifies diamonds based on the newly introduced 'quality' feature.
- Hyperparameter optimization led to a marked increase in the predictive performance of the models.

## Technologies Used
- Regression Models: Linear Regression, Ridge Regression, Logistic Regression.
- Data Balancing: SMOTE.
- Evaluation Metric: Mean Squared Error (MSE), Accuracy.
- Hyperparameter Tuning: Learning Rate Scheduler.


<!-- CONCLUSION -->
## Conclusion

The project successfully demonstrates the use of regression analysis and hyperparameter optimization in predicting diamond prices and quality. The introduction of the 'quality' feature and the strategic use of SMOTE highlight the project's innovative approach to tackling real-world data challenges.