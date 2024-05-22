# Diabetes-Prediction-from-Health-Indicators

#### Introduction
Diabetes is a chronic disease affecting millions of people worldwide, often leading to severe health complications if not diagnosed and treated early. This project aims to predict the risk of diabetes using health indicators through the application of machine learning techniques. By analyzing a comprehensive dataset and employing various models, the project seeks to identify key factors contributing to diabetes risk and provide accurate predictions.

#### Description
This project focuses on the classification of diabetes risk using health indicators from a large dataset. The project involves extensive data preparation, exploratory data analysis (EDA), and the application of various machine learning algorithms to predict diabetes risk. Utilizing Python and its libraries, we meticulously clean the dataset, explore correlations, and evaluate the performance of different models to determine the most effective approach for diabetes prediction.

#### Objectives
- **To clean and prepare the diabetes dataset for analysis.**
- **To visualize and analyze health indicators and their correlation with diabetes.**
- **To build and compare multiple machine learning models for diabetes prediction.**
- **To evaluate model performance and select the best model for accurate predictions.**

#### Data Source
The primary dataset was sourced from the Behavioral Risk Factor Surveillance System (BRFSS), encompassing health indicators of US citizens. The dataset includes 253,680 rows and 22 columns, with a binary target variable indicating diabetes status.

**Data Source:** [Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data)

#### Methodology
1. **Data Sourcing and Cleaning:**
   - Acquired from the BRFSS database.
   - Extensive preprocessing to handle missing data, duplicates, and outliers.

2. **Exploratory Data Analysis (EDA):**
   - Utilized Python libraries (Pandas, Matplotlib, Seaborn, NumPy) for data visualization and analysis.
   - Examined the distribution of health indicators and their relationship with diabetes.

3. **Model Building and Evaluation:**
   - Implemented various machine learning models: k-NN, Classification Trees, Naïve Bayes, Logistic Regression, Neural Networks, and Random Forests.
   - Performed feature selection using PCA and chi-square tests for dimensionality reduction.

4. **Model Performance Evaluation:**
   - Evaluated models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
   - Applied SMOTE to address class imbalance and improve model performance.

#### Key Findings
- **Achieved highest accuracy of 89% with the Random Forest model.**
- **Identified significant health indicators** that correlate with diabetes risk.
- **Explored the impact of various health and lifestyle factors** on diabetes prediction.
- **Demonstrated the effectiveness of ensemble methods** in improving prediction accuracy.

#### Limitations and Future Work
- **Limitations:**
  - Model reliance on the quality and completeness of health indicator data.
  - Potential biases in the dataset due to self-reported information.

- **Future Work:**
  - Investigate additional health indicators and their impact on diabetes risk.
  - Explore the use of more advanced machine learning techniques.
  - Enhance model interpretability to better understand the influence of individual predictors.

#### Conclusion
This project provides valuable insights into the factors influencing diabetes risk and demonstrates the application of machine learning for disease prediction. The methodologies and findings can serve as a foundation for further research and development of predictive models in healthcare.
