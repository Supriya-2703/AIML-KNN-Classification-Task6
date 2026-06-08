# K-Nearest Neighbors (KNN) Classification using Heart Disease Dataset

## 📌 Objective

The objective of this project is to understand and implement the K-Nearest Neighbors (KNN) algorithm for classification tasks. The model is trained to predict the presence of heart disease based on patient health attributes and evaluate its performance using various metrics.

## 🛠 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## 📂 Dataset

Used the Heart Disease Dataset for classification analysis and prediction.

### Dataset Information

* 1025 records
* 13 input features
* 1 target variable (`target`)

  * 0 = No Heart Disease
  * 1 = Heart Disease

## 🔍 Tasks Performed

* Imported and explored the dataset.
* Performed data preprocessing and analysis.
* Normalized features using StandardScaler.
* Split the dataset into training and testing sets.
* Implemented K-Nearest Neighbors (KNN) Classifier.
* Experimented with different values of K.
* Evaluated model performance using accuracy score.
* Generated confusion matrix for classification analysis.
* Visualized the relationship between K values and accuracy.
* Created decision boundary visualization using selected features.

## 📊 Output

* Trained KNN Classification model.
* Accuracy scores for different K values.
* Best K value selection.
* Confusion Matrix.
* K vs Accuracy graph.
* Decision Boundary visualization.

## 📁 Files Included

* heart.csv
* Task 6.ipynb
* README.md
* knn_accuracy_plot.png
* confusion_matrix.png
* decision_boundary.png

## 📈 Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## 🔬 K Value Analysis

Different values of K were tested to determine the optimal number of neighbors. The model performance was compared across multiple K values, and the best-performing K was selected based on accuracy.

## 🚀 Conclusion

This project provided practical experience with the K-Nearest Neighbors algorithm for classification tasks. By normalizing features and testing different K values, the model successfully classified heart disease cases and demonstrated how distance-based learning can be applied to real-world healthcare datasets.
