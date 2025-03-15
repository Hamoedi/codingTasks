# Logistic Regression on Iris Dataset

## Description
This project builds a **Logistic Regression Classifier** to classify iris flowers based on their features. The goal is to predict whether a given flower belongs to the **Iris-setosa** class or not. The project involves binary classification first and then extends to a **multi-class classification** problem including all three species: **Iris-setosa, Iris-versicolor, and Iris-virginica**.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hamoedi/codingTasks.git
   cd codingTasks/Iris_Logistic_Regression
   ```
2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```
3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
After installation, you can run the Jupyter Notebook or Python script directly:

**To run in Jupyter Notebook:**
```bash
jupyter notebook iris_logistic_regression.ipynb
```

**To run as a Python script:**
```bash
python iris_logistic_regression.py
```

### Steps Performed in the Project:
- Load the **Iris dataset** and preprocess it.
- Perform **binary classification** (Iris-setosa vs. Not Iris-setosa).
- Encode the dependent variable appropriately.
- Split the dataset into training and test sets.
- Train a **Logistic Regression** model and evaluate its performance.
- Generate a **confusion matrix** to analyze model accuracy.
- Manually calculate **accuracy, precision, and recall**, and compare results with scikit-learn.
- Extend the problem to a **multi-class classification** setting (classifying all three species).
- Observe changes in performance and confusion matrix behavior.

## Screenshots
Below is an example of the confusion matrix visualization:

![Confusion Matrix](https://github.com/user-attachments/assets/27071084-aa92-4b58-894d-a42414731f79)


## Credits
- **Author:** [Ahmed Al Waly](https://github.com/Hamoedi)


