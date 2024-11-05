## **Heart Disease Prediction Using Machine Learning and Deep Learning**
## Introduction
Heart disease is a significant global health concern, often leading to severe complications and high mortality rates. The ability to predict heart disease risk early on can be crucial for effective intervention and management. This project harnesses the power of data analysis and predictive modeling to evaluate various health indicators that contribute to heart disease risk.

By utilizing an extensive dataset of patient health metrics, the project explores different Machine Learning (ML) and Deep Learning (DL) techniques. These methods range from traditional algorithms like Logistic Regression to more complex architectures such as Neural Networks. The goal is to create a reliable predictive framework that aids healthcare professionals in identifying at-risk individuals, ultimately enhancing patient care and outcomes.

## Dataset
The dataset used for the Heart Disease Prediction project is the **Heart Disease UCI** dataset, which contains various health-related attributes that can help predict the presence of heart disease in patients. 

### Dataset Details:
- **Source**: The dataset is publicly available on the UCI Machine Learning Repository.
- **Number of Instances**: 303
- **Number of Features**: 14 (including the target variable)
  
### Features:
1. **age**: Age of the patient (in years)
2. **sex**: Sex of the patient (1 = male; 0 = female)
3. **cp**: Chest pain type (0-3)
4. **trestbps**: Resting blood pressure (in mm Hg)
5. **chol**: Serum cholesterol (in mg/dl)
6. **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. **restecg**: Resting electrocardiographic results (0-2)
8. **thalach**: Maximum heart rate achieved
9. **exang**: Exercise induced angina (1 = yes; 0 = no)
10. **oldpeak**: ST depression induced by exercise relative to rest
11. **slope**: Slope of the peak exercise ST segment (0-2)
12. **ca**: Number of major vessels (0-3) colored by fluoroscopy
13. **thal**: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversable defect)
14. **target**: Diagnosis of heart disease (1 = presence; 0 = absence)

### Missing Values:
- The dataset does not contain any missing values, ensuring complete records for analysis.

This dataset provides a comprehensive foundation for training various machine learning and deep learning models to predict heart disease, making it an essential resource for the project.


## Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is a critical step in the data science workflow that allows us to understand the underlying patterns and characteristics of the dataset. In this project, we performed various analyses to uncover insights related to heart disease.

During the EDA phase of the Heart Disease Prediction project, the following steps were taken:

1. **Data Overview**: Examined the structure of the dataset, including the number of rows and columns, data types, and missing values.

2. **Descriptive Statistics**: Generated summary statistics for numerical features.

3. **Correlation Analysis**: Created a correlation matrix to identify relationships between features and the target variable.

4. **Data Visualization**:
   - Generated count plots to visualize the distribution of categorical features.
   - Created box plots to analyze the spread of numerical features and identify outliers.
   - Used heatmaps to visualize the correlation matrix.
   - Developed scatter plots to observe relationships between numerical variables.

5. **Feature Distribution**: Analyzed the distribution of features to assess skewness and kurtosis.

## Visualizations
During the EDA, the following visualizations were created:

1. Count plots to visualize the distribution of heart disease across different categories.
2. Box plots to analyze the spread of numerical features and identify outliers.
3. Heatmap to illustrate the correlation matrix of the features.
4. Scatter plots to observe relationships between key numerical variables.
5. Distribution plots to assess the distribution of individual features.

## Modeling
The project employs several algorithms, including:

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Decision Tree
- Random Forest
- XGBoost
- Neural Network

Each model is trained and evaluated to determine its effectiveness in predicting heart disease risk.

## Evaluation Metrics
The performance of the models is measured using the following metrics:

- Accuracy Score
- F1 Score
- Precision Score
- Recall Score

## Results
The following key results were obtained from the modeling and evaluation of the heart disease dataset:

1. **Logistic Regression**:
   - Accuracy Score: 0.85
   - F1 Score: 0.80
   - Precision Score: 0.78
   - Recall Score: 0.82

2. **Naive Bayes**:
   - Accuracy Score: 0.78
   - F1 Score: 0.74
   - Precision Score: 0.76
   - Recall Score: 0.72

3. **Support Vector Machine**:
   - Accuracy Score: 0.82
   - F1 Score: 0.78
   - Precision Score: 0.79
   - Recall Score: 0.77

4. **K-Nearest Neighbors**:
   - Accuracy Score: 0.80
   - F1 Score: 0.76
   - Precision Score: 0.75
   - Recall Score: 0.77

5. **Decision Tree**:
   - Accuracy Score: 0.83
   - F1 Score: 0.79
   - Precision Score: 0.80
   - Recall Score: 0.78

6. **Random Forest**:
   - Accuracy Score: 0.88
   - F1 Score: 0.85
   - Precision Score: 0.84
   - Recall Score: 0.86

7. **XGBoost**:
   - Accuracy Score: 0.87
   - F1 Score: 0.84
   - Precision Score: 0.83
   - Recall Score: 0.85

8. **Neural Network**:
   - Accuracy Score: 0.86
   - F1 Score: 0.83
   - Precision Score: 0.82
   - Recall Score: 0.84

These results indicate that the Random Forest algorithm achieved the highest accuracy score, suggesting it is the most effective model for predicting heart disease based on the features in the dataset.


## Contact
For questions or feedback, feel free to reach out:

- **Name**: Jatin Choudhury
- **Email**: JatinChoudhury419@gmail.com
- **GitHub**: Jatin419


