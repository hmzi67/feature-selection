# Human Activity Recognition - Feature Selection

This project focuses on predicting human activities such as standing using sensor data from accelerometers and gyroscopes. The dataset includes numerous features, and the primary objective is to select the most relevant ones to enhance prediction accuracy.

## Dataset
- **Source**: Human Activity Recognition with Smartphones
- **Link**: [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones?select=test.csv)
- **Files**:
  - `train.csv`: Training dataset.
  - `test.csv`: Testing dataset.

## Feature Selection Process

### 1. Duplicate Feature Removal
- Identified and removed duplicate features to reduce redundancy.

### 2. Variance Threshold
- Applied variance threshold to filter out features with low variance, ensuring only those with significant variability were retained.

### 3. Correlation Analysis
- Conducted correlation analysis to remove highly correlated features, reducing multicollinearity and improving model performance.

### 4. ANOVA (Analysis of Variance)
- Utilized ANOVA to select the top 100 features that contribute most significantly to the predictive model.

## Model Training
- **Algorithm**: Logistic Regression
- **Accuracy**: Achieved a high accuracy of 98% with the reduced feature set.

## Key Benefits of Feature Selection
- **Improved Model Performance**: Reduced overfitting and computational complexity by focusing on the most important features.
- **Interpretability**: Enhanced the interpretability of the model by reducing the number of input features.

## Conclusion
This project demonstrates the effectiveness of feature selection in building efficient and accurate models for human activity recognition. By applying various feature selection techniques, we were able to significantly reduce the dataset's dimensionality while maintaining high prediction accuracy.
