# SVM_cancer

## Machine learning and Python 
### TITLE: Cancer prediction

### AIM: The aim of this project is to develop a machine learning model using Support Vector Machines to classify human cell records and predict whether cell samples are benign or malignant thereby assisting in early cancer detection.

### DATA DESCRIPTION: The dataset used for this project was sourced from the UCI Machine Learning Repository and contains 699 samples of human cell data for breast cancer classification. Each sample represents features extracted from images of cell nuclei obtained during a fine needle aspiration (FNA) of a breast mass.

- Number of features: There are 9 features

- Target variables: Class(Benign = 2.0, malignant = 4.0)

### DEVELOPMENT PROCESS: 
- Data loading and preparation: Data loading and preparation: Libraries such as Pandas, NumPy (for data manipulation), matplotlib.pyplot, pylab (for visualization), scipy.optimize (for optimization), sklearn.preprocessing (for machine learning preprocessing), and %matplotlib inline (for notebook display) are imported.

- Exploratory Data Analysis: Data exploration was carried out to understand the distribution and characteristics of features and response variables, data quality issues, summary statistics and visualization.

- Model Development: Support Vector Machine is developed using the sklearn library then the model is trained on the historical cell samples data, to learn the patterns associated with the medication responses.

- Model Evaluation: The model’s accuracy is accessed using the accuracy score function from the metrics module in sklearn. A confusion metrix is generated to evaluate its performance across the various classes. Additionally, jaccard score is used to measure the similarity between the predicted and actual labels, helping to evaluate the overlap between the true positives and the predicted positives for each class.

### EVALUATION RESULT:
- Accuracy: The model achieved a high accuracy of 96% which indicates a good performance across both classes.
- Confusion Matrix: The model has excellent performance on class 4, with no misclassifications (100%). For class 2, the model also performs well, correctly identifying most samples, with only 5 misclassified as class 4 (94%)
- Jaccard score: Jaccard score of 94% (class 2) and 90% (class 4) shows that the model has a strong predictive power for both classes.

### CONCLUSION
Using a highly accurate Support Vector Machine model for breast cancer classification with an accuracy of 96% and high Jaccard scores for both benign and malignant classes, this demonstrates the model as a potentially valuable tool for early cancer detection.

