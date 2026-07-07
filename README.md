# Why 81% Accuracy Wasn’t Enough

This project was completed as part of my postgraduate studies in Data Science at Technological University Dublin.

The objective was to predict whether supermarket customers would purchase organic products.

The project compares several classification models and shows why overall accuracy alone was not enough to evaluate whether the model supported the business objective.

## Key insight

Logistic Regression achieved approximately 81.3% accuracy, but it still missed 630 actual organic buyers.

Naive Bayes achieved lower accuracy, approximately 73.9%, but identified a higher proportion of actual buyers.

This shows why model evaluation should consider the type of errors being made, not only the headline accuracy score.

## Models compared

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbours
- Naive Bayes

## Main metrics

| Model | Accuracy | Buyer Recall | Missed Buyers |
|---|---:|---:|---:|
| Logistic Regression | 81.3% | 43% | 630 |
| Random Forest | 80.7% | 42% | 647 |
| Naive Bayes | 73.9% | 65% | 386 |

## Article

The Medium article is available here:

[Add Medium link]
