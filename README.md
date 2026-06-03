# Network Intrusion Detection System (NIDS)

A machine learning-based Network Intrusion Detection System developed using classical AI and machine learning techniques on a balanced NSL-KDD derived dataset.

## Features

* Rule-Based Reflex Agent
* K-Nearest Neighbours (KNN)
* Gaussian Naïve Bayes
* Logistic Regression
* K-Means Clustering
* Genetic Algorithm Feature Selection

## Dataset

* 6,000 network connection records
* 15 numerical features
* Binary classification:

  * 0 = Normal Traffic
  * 1 = Attack Traffic

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| KNN (k=1)           | 95.75%   |
| Logistic Regression | 91.50%   |
| K-Means Clustering  | 87.00%   |
| Reflex Agent        | 84.33%   |
| Naïve Bayes         | 78.75%   |

## Repository Structure

```text
NIDS_Project.ipynb   # Complete implementation
report.pdf           # Detailed project report
README.md            # Project documentation
```

## How to Run

1. Place `network_traffic.csv` in the project directory.
2. Open `NIDS_Project.ipynb`.
3. Run all notebook cells from top to bottom.

## Techniques Used

* Data Exploration & Visualization
* Rule-Based AI Agents
* Supervised Learning
* Unsupervised Learning
* Feature Scaling
* Dimensionality Reduction (PCA)
* Genetic Algorithms

## Key Takeaways

* KNN achieved the highest accuracy (95.75%).
* K-Means successfully separated classes without labels.
* Genetic Algorithm reduced the feature set from 15 to 12 features while slightly improving Logistic Regression performance.
* Feature engineering and selection significantly impact intrusion detection performance.
