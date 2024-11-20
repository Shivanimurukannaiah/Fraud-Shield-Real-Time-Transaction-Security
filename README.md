# Credit Card Fraud Detection

A machine learning project to detect fraudulent transactions in credit card data. This project uses Python and popular data science libraries to preprocess the dataset, train classification models, and evaluate their performance.

---

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Project Structure](#project-structure)
6. [Usage](#usage)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

---

## Overview

Credit card fraud is a critical issue faced by financial institutions. This project aims to:
- Analyze credit card transaction data.
- Build machine learning models to classify transactions as legitimate or fraudulent.
- Compare the performance of different algorithms.

---

## Dataset

The dataset used for this project is publicly available on [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). Key features of the dataset:
- **284,807 transactions**, including **492 fraudulent ones**.
- Features include anonymized numerical values and a `Class` label: 
  - `0`: Legitimate transaction.
  - `1`: Fraudulent transaction.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `numpy` and `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `scikit-learn` for model building and evaluation.
  - `imbalanced-learn` for handling class imbalance.

---

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
