# Parkinson-s-Disease
This code performs classification and model evaluation on a Parkinson’s Disease dataset using various machine learning algorithms such as Logistic Regression, Support Vector Machines (SVM), Naive Bayes, Random Forest, and K-Nearest Neighbors (KNN). The dataset contains features like spread1 and spread2, which help classify whether a patient is affected by Parkinson's Disease or not. By splitting the dataset into training and test sets, standardizing features, and applying different classifiers, this code compares the performance of multiple models. It evaluates the models using accuracy, precision, recall, F1-score, and confusion matrix, making it valuable for identifying the most efficient algorithm for Parkinson’s detection.

Key Points on the Working:
- Data Loading*: The dataset is loaded using pandas.read_csv and processed for missing values and basic information.
- Feature Selection*: Features (spread1, spread2) are selected for classification, while the target variable is status.
- Data Splitting*: The dataset is split into training and test sets using train_test_split.
- Standardization*: Features are standardized using StandardScaler to ensure that they contribute equally to model training.
- Model Training*: Several machine learning classifiers are trained, including Logistic Regression, SVM, Naive Bayes, Random Forest, and KNN.
- Performance Evaluation*: Each model's performance is evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
- Decision Boundaries*: The decision boundaries of each classifier are visualized using contour plots for a better understanding of model decisions.
- Model Comparison*: A dictionary of models is used to automate training and evaluation, displaying the performance metrics for each classifier.
