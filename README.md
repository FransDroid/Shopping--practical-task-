# Shopping Intent Classifier

This project implements a k-nearest neighbor classifier to predict whether a user browsing an online shopping website will make a purchase. The model uses user session data, such as the number of pages visited and browsing patterns, to classify purchasing intent.

---

## Features

- Predicts purchasing intent based on user session data.
- Measures performance using **sensitivity** (true positive rate) and **specificity** (true negative rate).
- Uses k-nearest neighbors (k=1) for classification.

---

## Prerequisites

### Dependencies

- Python 3.6+
- Required Python packages:
  - `scikit-learn`
  - `shopping.csv`

Install `scikit-learn` using pip if it's not already installed:

```bash
pip3 install scikit-learn
```

### Usage

Running the Program

1. Clone this repository or download the files.
2. Ensure the dataset (shopping.csv) is in the same directory as the script.
3. Run the program:

```bash
python shopping.py shopping.csv
```

Output

The program will:

1. Load the data and split it into training and testing sets.
2. Train a k-nearest neighbors model.
3. Evaluate the model’s performance and display results, including:
   • Correct and incorrect classifications
   • True Positive Rate (Sensitivity)
   • True Negative Rate (Specificity)

Sample output:

```bash
Correct: 4105
Incorrect: 827
True Positive Rate: 39.22%
True Negative Rate: 91.31%
```
