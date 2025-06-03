# Iris Classification using K-Nearest Neighbors (KNN)

This project applies the **K-Nearest Neighbors (KNN)** algorithm to classify Iris flowers into three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

It uses the classic **Iris dataset** and evaluates performance using **accuracy, classification report**, and **confusion matrix** for multiple values of K.

---

## Dataset

- **Source:** `Iris.csv`
- Features:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- Target:
  - Species (multi-class: 3 categories)
  Load and preprocess the data

1.Drop the Id column.
Split data into features (X) and target (y).

2.Train-Test Split
80% training, 20% testing.

3.Standardize Features
Using StandardScaler.

4.Train KNN Classifier
Loop over different K values (e.g., 1 to 5).
Measure accuracy and print classification report.

5.Visualize Confusion Matrix
For each K, plot the confusion matrix.

