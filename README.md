# Network Intrusion Detection using Machine Learning

This project focuses on the use of machine learning models for network intrusion detection. The code uses the KDD Cup dataset, which contains a variety of network traffic instances, including normal traffic and different types of intrusions.

## Dataset Information

The dataset consists of various features related to network activity, such as duration, protocol type, service, flag, source and destination bytes, and more. The target variable includes different attack types, categorized into five classes: normal, DoS (Denial of Service), probe, R2L (Unauthorized access from a remote machine), and U2R (Unauthorized access to privileged local user).

## Code Overview

1. **Data Preprocessing:**
   - Reading the dataset and understanding the features and attack types.
   - Handling missing values and dropping unnecessary columns.
   - Visualizing correlation between features.

2. **Feature Selection:**
   - Calculating information gain for each feature to select the top k features.
   - Using chi-squared test for feature selection.

3. **Model Training:**
   - Utilizing various machine learning models for intrusion detection.
   - Models include Decision Tree, KMeans clustering, Naive Bayes, Support Vector Machine (SVM), and Artificial Neural Network (ANN).

4. **Evaluation Metrics:**
   - Computing accuracy, confusion matrix, sensitivity, specificity, false positive rate, and Matthews correlation coefficient for each model.
   - Plotting ROC curves and calculating AUC (Area Under the Curve).

5. **Model Comparison:**
   - Evaluating and comparing the performance of different models on the given dataset.

## How to Use

1. Clone the repository:
   ```bash
   git clone (https://github.com/Fatim-Sohail/Network-Traffic-Classification-and-Intrusion-Detection-ML-Analysis.git)
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
3. Run the Jupyter Notebook:
Explore the code, experiment with different models, and analyze the results.

Feel free to contribute, report issues, or suggest improvements. Happy coding!

Make sure to replace "your-username" with your actual GitHub username in the
