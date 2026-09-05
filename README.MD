# Red Wine Quality Prediction

A Machine Learning project focused on analyzing and predicting **red wine quality** using chemical properties of wine and several classification algorithms.

This project explores a complete beginner-to-intermediate Machine Learning workflow, including data preprocessing, exploratory data analysis, feature scaling, model training, and model evaluation using Python and Scikit-learn.

---

## Project Overview

The goal of this project is to build classification models that can predict the quality of red wine based on its physicochemical properties.

The dataset contains various chemical measurements of red wine, which are analyzed to identify patterns and relationships between these features and wine quality.

### Main Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Visualization
   ↓
Data Preprocessing
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
```

---

## Features

* Exploratory Data Analysis (EDA)
* Data visualization
* Data preprocessing
* Label encoding
* Feature standardization
* Train-test splitting
* Classification model training
* Accuracy evaluation
* Confusion matrix analysis
* Comparison of multiple classification algorithms

---

## Machine Learning Models

This project experiments with several classification algorithms:

### Logistic Regression

Used as a baseline classification model to establish an initial performance benchmark.

### Decision Tree Classifier

A tree-based classification algorithm used to identify decision rules from the dataset features.

### Support Vector Machine (SVM)

A classification algorithm that attempts to find an optimal decision boundary between different classes.

---

## Tech Stack

### Programming Language

* Python

### Data Analysis

* NumPy
* Pandas

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn

### Development Environment

* Jupyter Notebook

---

## Libraries

```python
import numpy as np
import pandas as pd

import matplotlib.pyplot as plt
import seaborn as sns

from sklearn import preprocessing
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import StandardScaler

from sklearn.model_selection import train_test_split

from sklearn.metrics import accuracy_score
from sklearn.metrics import confusion_matrix

from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier

from sklearn import svm
from sklearn import metrics
```

---

## Project Structure

```text
Prediksi-Kualitas-Anggur-Merah/
│
├── data/
│   ├── raw/
│   │   └── winequality-red.csv
│   │
│   └── processed/
│
├── notebooks/
│   └── Wine-Quality.ipynb
│
├── src/
│
├── Wine/
│   └── Python virtual environment
│
└── README.md
```

> The `Wine/` directory is a local Python virtual environment and should generally be excluded from version control using `.gitignore`.

---

## Dataset

The project uses the **Red Wine Quality Dataset** stored at:

```text
data/raw/winequality-red.csv
```

The dataset contains physicochemical measurements of red wine samples and their corresponding quality ratings.

The features can be used to investigate how chemical properties relate to the resulting wine quality.

---

## Data Preprocessing

Several preprocessing techniques are explored in the project, including:

* Label Encoding
* Feature Scaling using `StandardScaler`
* Train-test splitting

These steps prepare the dataset for use with the classification algorithms.

---

## Model Evaluation

The models are evaluated using:

### Accuracy Score

Measures the proportion of correctly classified samples.

### Confusion Matrix

Used to examine the classification results across the different target classes.

Additional metrics from Scikit-learn are also available for evaluating model performance.

> Model performance results are documented in the Jupyter Notebook.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Prediksi-Kualitas-Anggur-Merah.git
```

```bash
cd Prediksi-Kualitas-Anggur-Merah
```

### 2. Create a Virtual Environment

```bash
python -m venv Wine
```

### 3. Activate the Environment

#### Linux / macOS

```bash
source Wine/bin/activate
```

#### Windows

```bash
Wine\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 5. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Wine-Quality.ipynb
```

---

## Learning Objectives

This project was developed to strengthen practical understanding of the Machine Learning workflow, particularly:

* Python for Data Science
* Data manipulation with Pandas
* Numerical computing with NumPy
* Data visualization
* Exploratory Data Analysis
* Data preprocessing
* Feature scaling
* Classification algorithms
* Model evaluation
* Interpreting Machine Learning results

---

## Future Improvements

Potential improvements for this project include:

* More comprehensive exploratory data analysis
* Feature engineering
* Cross-validation
* Hyperparameter tuning
* Additional classification algorithms
* Random Forest
* Gradient Boosting
* XGBoost
* Improved class balancing
* Model comparison using multiple evaluation metrics
* Deployment with Streamlit

---

## Project Status

**Completed — Learning Project**

The project currently focuses on experimentation with classical Machine Learning classification algorithms and understanding the end-to-end workflow from raw data to model evaluation.

---

## Author

**Dika**

Data Science Student interested in:

* Machine Learning
* Artificial Intelligence
* Data Science
* Software Engineering

---

## License

This project is intended for educational and learning purposes.
