# Breast Cancer Classification

A machine learning project to classify breast tumours as benign or malignant 
using the Breast Cancer Wisconsin dataset.

## Models Used
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest ← best performing model

## Results
| Model | Accuracy | Recall |
|---|---|---|
| SVM (Linear) | 97.2% | 96.23% |
| Logistic Regression | 95.8% | 94.34% |
| Random Forest | 97.2% | 98.11% |

## Libraries
Python, scikit-learn, pandas, numpy, matplotlib, seaborn

## Key Finding
Random Forest was selected as the final model due to its superior Recall (98.11%), 
the most critical metric in medical diagnosis where missing a malignant case 
carries significant clinical risk
