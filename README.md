Machine Learning Algorithms: K-Means, KNN, and Naive Bayes
This repository contains explanations, real-world examples, and implementations of three important machine learning algorithms: K-Means, K-Nearest Neighbors (KNN), and Naive Bayes.


1. K-Means Clustering
Overview
Type: Unsupervised Learning
Goal: Partition data into K clusters based on similarity.
How it works:
Choose K (number of clusters).
Randomly initialize centroids.
Assign each point to the nearest centroid.
Update centroids by taking the mean of assigned points.
Repeat until convergence.

Real-World Applications
Customer segmentation in marketing.
Document or image clustering.
Anomaly detection (e.g., fraud detection).


2. K-Nearest Neighbors (KNN)
Overview
Type: Supervised Learning (Classification & Regression).
Goal: Predict class/label based on the majority vote or average of the K nearest neighbors.
How it works:
Choose a value of K.
Calculate distance (e.g., Euclidean) between the query point and all training points.
Select the K closest neighbors.
Predict based on majority class (classification) or average (regression).

Real-World Applications
Recommendation systems.
Handwriting or OCR recognition.
Predicting diseases based on patient history.


3. Naive Bayes
Overview
Type: Supervised Learning (Classification).
Based on: Bayes’ Theorem with the “naive” assumption that features are independent.
Formula:
P(Y∣X)=P(X)P(X∣Y)⋅P(Y)​
Often used for text classification.

Real-World Applications
Spam email detection.
Sentiment analysis.
Medical diagnosis.


Comparison
K-Means → Type: Unsupervised, Clustering | Pros: Simple, efficient | Cons: Requires K, sensitive to outliers
KNN → Type: Supervised, Classification/Regression | Pros: Easy to understand, no training phase | Cons: Slow for large datasets, sensitive to noise
Naive Bayes → Type: Supervised, Classification | Pros: Works well with text, fast | Cons: Assumes feature independence


How to Run

1.Clone the repository:
git clone <repo-url>

2.Install dependencies:
pip install -r requirements.txt

3.Run Jupyter Notebook or Python files for each algorithm:
jupyter notebook


Repository Structure
├── kmeans/
│   └── kmeans_example.ipynb
├── knn/
│   └── knn_example.ipynb
├── naive_bayes/
│   └── naive_bayes_example.ipynb
└── README.md
