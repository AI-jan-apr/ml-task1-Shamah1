# Breast Cancer — Binary Classification

## Objective
Predict whether a tumor is Malignant (0) or Benign (1)

## Dataset
- 569 samples, 30 features
- Source: Breast Cancer Wisconsin (sklearn)
- No missing values

## Models
- Logistic Regression
- SVM
- KNN

## Results
| Model | Accuracy | Precision | Recall | F1 |
|-------|----------|-----------|--------|----|
| Logistic Regression | 0.9649 | 0.9595 | 0.9861 | 0.9726 |
| SVM | 0.9298 | 0.9211 | 0.9722 | 0.9459 |
| KNN | 0.9123 | 0.9429 | 0.9167 | 0.9296 |

## Conclusion
Best Model: Logistic Regression  
Most Important Metric: Recall — missing a real cancer patient is dangerous

## Project Structure
```
breast-cancer-binary-classification/
├── modeling.ipynb
└── README.md
```


