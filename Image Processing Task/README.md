
# Optical Digits Classification using Random Forest

## Description
This project builds a **Random Forest Classifier** to classify handwritten digits from the Optical Digits dataset. The model undergoes hyperparameter tuning, performance evaluation, and an in-depth analysis of classification accuracy, precision, recall, and F1-score. Understanding digit classification is essential for applications in Optical Character Recognition (OCR) and AI-powered handwriting recognition.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hamoedi/codingTasks.git
   cd codingTasks/OptDigits_Classification
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
jupyter notebook optdigits_task.ipynb
```

**To run as a Python script:**
```bash
python optdigits_task.py
```

### Steps Performed in the Project:
- Load the **Optical Digits dataset** and preprocess it.
- Split the dataset into **training and test sets**, ensuring a fair evaluation.
- Train a **Random Forest Classifier** to classify handwritten digits.
- Tune the **max_depth** parameter to optimize model performance.
- Select the best **max_depth** value using **GridSearchCV**.
- Generate a **confusion matrix** to analyze classification errors.
- Identify the class with the highest misclassification count.
- Compute and report **accuracy, precision, recall, and F1-score** with `average="macro"`.

## Screenshots
Below is an example of the confusion matrix visualization:

![Confusion Matrix](https://github.com/user-attachments/assets/733c9cbb-6e7b-419d-922a-2e6fb868a464)


## Credits
- **Author:** [Ahmed Al Waly](https://github.com/Hamoedi)

