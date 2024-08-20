# Metabolic Syndrome Prediction (90,5% accuracy)

### Project Overview
This project focuses on predicting the presence of Metabolic Syndrome using a dataset containing various health-related features. The analysis includes data preprocessing, feature importance analysis, and the application of machine learning models to evaluate the likelihood of Metabolic Syndrome based on selected features.

### Tools and Libraries Used

**Python:** The core programming language used.

**Pandas:** For data manipulation and analysis.

**NumPy:** For numerical operations.

**Seaborn and Matplotlib:** For data visualization.

**Scikit-learn:** For machine learning models, including RandomForestClassifier and GradientBoostingClassifier, and for model evaluation metrics.

### Key Steps in the Project

#### 1) Data Loading and Preprocessing:
Loaded the dataset and checked for missing values.
Performed basic data cleaning by filling missing values with the mean.
Selected relevant features for analysis.

#### 2) Model Building and Evaluation:
Split the data into training and test sets.
Built a machine learning pipeline using StandardScaler and RandomForestClassifier.
Trained the model and evaluated its performance using accuracy, classification report, and confusion matrix.

#### 3) Feature Importance Analysis:
Analyzed and visualized the importance of each feature in predicting Metabolic Syndrome using Seaborn and Matplotlib.

#### 4) Results
The RandomForestClassifier was used to determine the importance of features such as Blood Glucose, Waist Circumference, and BMI in predicting Metabolic Syndrome. The confusion matrix and classification report provided insights into the model's accuracy and performance.

The model achieved 90,5% accuracy.

## Insights 
After applying machine learning models, the main features have changed. Initially, Waist Circumference appeared to be the most influential factor. 
However, after using machine learning, Blood Glucose emerged as the key feature. 
This shift is likely due to the machine learning model's ability to capture complex, non-linear relationships in the data that simple correlation analysis may have missed.

#### How to Run
Clone the repository.
Install the required libraries listed in requirements.txt.
Run the Jupyter notebook to see the analysis and results.
