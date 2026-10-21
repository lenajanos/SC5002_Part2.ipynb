# SC5002 Lab Assignment Part 2

**Course:** SC5002 Artificial Intelligence Fundamentals & Applications, NTU
**Author(s):** Lena Janos

## Overview
In this part of the project, I compare Linear Regression and Ridge Regression on a sample of the California Housing dataset, using 5-fold cross-validation.

## Repository contents
- `SC5002_Part2.ipynb` : the Colab notebook (Tasks 2.1-2.3)
- `model_comparison.png` : the performance chart from Task 2.3
- `README.md` : this file

## How to run
1. Open the notebook in Google Colab https://colab.research.google.com/drive/1iOeRGIzl6pz3mwHom2vHRaqVIT0Oh1Gb#scrollTo=4slNBAn8Poa-.
2. Run the cells in order.
3. No extra installs are needed. Colab already has numpy, pandas, matplotlib and scikit-learn.

## Method
- Linear Regression and Ridge Regression (alpha = 0.1, 10.0, 1000.0)
- Evaluation: mean R² over 5-fold cross-validation on the training set

## Results
| Model | Mean 5-fold R² |
|---|---|
| Linear Regression | 0.6457 |
| Ridge (alpha = 0.1) | 0.6457 |
| Ridge (alpha = 10.0) | 0.6443 |
| Ridge (alpha = 1000.0) | 0.3574 |

Refer to `model_comparison.png` for the Performance Comparison.

## Key findings
Understood:
- how to read the California Housing Dataset table,
- the importance of using cross validation, instead of a single split,
- the use of ridge penalty and why choosing a very hight value of alpha results in R^2 score dropping.

## Use of Generative AI
I used Claude for explaining concepts and understanding the code, the full prompt log is in the PDF report.
