# K-Means Clustering on Country Data

## Description
This project implements **K-Means Clustering** to analyze and group countries based on socio-economic and health indicators. The dataset includes various features such as GDP per capita (GDPP), child mortality, inflation, and more. The goal is to cluster similar countries and interpret their economic and developmental status.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hamoedi/codingTasks.git
   cd codingTasks/KMeans_Country_Clustering
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
jupyter notebook kmeans_task.ipynb
```

**To run as a Python script:**
```bash
python kmeans_task.py
```

### Steps Performed in the Project:
- Load the **Country-data.csv** dataset.
- Remove any non-numeric columns to facilitate clustering.
- Generate **scatter plots** comparing GDPP with other variables.
- Normalize the dataset using **MinMaxScaler**.
- Determine the **optimal number of clusters** using the **Elbow** and **Silhouette Score** methods.
- Train a **K-Means clustering model** using the optimal cluster count.
- Report the **Silhouette Score** for the best model.
- Visualize the clusters for **Child Mortality vs GDPP** and **Inflation vs GDPP**.
- Label country groups based on their economic classification (Least Developed, Developing, Developed).

## Screenshots
Below is an example of the cluster visualization:

![Cluster Visualization](https://github.com/user-attachments/assets/f5577def-38d4-4d7d-b150-13ded37ef23f)

## Credits
- **Author:** [Ahmed Al Waly](https://github.com/Hamoedi)


