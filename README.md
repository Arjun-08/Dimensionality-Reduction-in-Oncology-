# Dimensionality-Reduction-in-Oncology

## Overview

This project demonstrates the application of dimensionality reduction techniques on a cancer patients dataset to simplify data analysis and uncover hidden patterns. By reducing the number of features, we aim to facilitate better visualization and improve the performance of machine learning models.

## Dataset

The dataset used in this project contains information on cancer patients, including demographic details, exposure to risk factors, and clinical symptoms. The dataset consists of the following features:

- Patient Id
- Age
- Gender
- Air Pollution
- Alcohol use
- Dust Allergy
- Occupational Hazards
- Genetic Risk
- Chronic Lung Disease
- Balanced Diet
- Obesity
- Smoking
- Passive Smoker
- Chest Pain
- Coughing of Blood
- Fatigue
- Weight Loss
- Shortness of Breath
- Wheezing
- Swallowing Difficulty
- Clubbing of Finger Nails
- Frequent Cold
- Dry Cough
- Snoring
- Level

## Project Workflow

### Data Preprocessing

1. **Loading the Dataset:** The dataset is loaded from an Excel file stored in Google Drive.
2. **Handling Missing Values:** Rows with missing values (encoded as 0 or 'Nan') are removed to ensure data quality.
3. **Label Encoding:** Categorical variables are encoded using label encoding to convert them into numerical values.
4. **Data Scaling:** The data is standardized using the `StandardScaler` to normalize the distribution of features.

### Dimensionality Reduction

1. **Principal Component Analysis (PCA):** PCA is applied to reduce the dimensionality of the dataset to 2 principal components, retaining the essential information while simplifying the data.

### Results

1. **Explained Variance:** The principal components explain a significant portion of the variance in the data.
2. **Visualization:** The reduced data is visualized using a scatter plot, with different colors representing different levels of cancer severity.
3. **Component Analysis:** The contribution of each original feature to the principal components is analyzed and presented.

### Correlation Analysis

A heatmap of the correlation matrix is generated to visualize the relationships between different features in the dataset.


## Conclusion

This project demonstrates the effectiveness of PCA in reducing the dimensionality of a complex dataset, making it easier to visualize and analyze. The correlation heatmap provides additional insights into the relationships between different features, highlighting potential areas for further research and analysis.


## Contact

If you have any questions or suggestions, please feel free to reach out to me at [nvarjunmani07@gmail.com](mailto:nvarjunmani07@gmail.com).

