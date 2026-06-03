# Iris Flower Classification using Machine Learning

## Project Overview

This project performs classification of Iris flower species using multiple Machine Learning algorithms and compares their performance.

The famous Iris dataset contains measurements of flower characteristics such as sepal length, sepal width, petal length, and petal width. The objective is to predict the species of an Iris flower based on these features.

The project covers the complete Machine Learning workflow:

* Data Collection
* Data Analysis and Visualization
* Data Cleaning
* Feature Selection
* Train-Test Split
* Feature Scaling
* Model Training
* Model Evaluation
* Model Comparison

---

## Dataset

Dataset: Iris Flower Dataset

The dataset contains 150 samples belonging to three different species:

| Species         | Samples |
| --------------- | ------- |
| Iris-setosa     | 50      |
| Iris-versicolor | 50      |
| Iris-virginica  | 50      |

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Variable

* Species

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset overview
* Statistical summary
* Missing value detection
* Duplicate value detection
* Correlation analysis
* Species distribution analysis
* Pairplot visualization

### Visualizations

* Species distribution pie chart
* Pairplot with species-based colouring
* Accuracy comparison bar chart

---

## Data Preprocessing

### Removed Unnecessary Column

The `Id` column was removed because it does not contribute to prediction.

### Train-Test Split

The dataset was divided into:

* Training Set: 80%
* Testing Set: 20%

Stratified sampling was used to maintain equal class distribution.

### Feature Scaling

Standardization was applied using:

```python
StandardScaler()
```

This ensures all features are on a similar scale before model training.

---

## Machine Learning Models Implemented

### 1. Logistic Regression

A linear classification algorithm suitable for multi-class classification problems.

### 2. K-Nearest Neighbors (KNN)

Classifies data points based on the nearest neighbouring samples.

### 3. Decision Tree Classifier

Creates a tree-like structure to make classification decisions.

### 4. Random Forest Classifier

An ensemble learning method that combines multiple decision trees.

### 5. Support Vector Machine (SVM)

Finds the optimal decision boundary between classes.

### 6. Gaussian Naive Bayes

Probabilistic classifier based on Bayes' theorem.

---

## Model Evaluation

Each model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

Metrics included:

* Precision
* Recall
* F1-Score

---

## Performance Comparison

The accuracies of all models were compared using a bar chart for visual analysis.

Models compared:

* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* SVM
* Naive Bayes

---

## Project Structure

```text
Iris-Dataset/
│
├── Iris.csv
├── Iris_dataset.ipynb
├── README.md
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/kousik2006/Iris-Dataset.git
```

### Move into the Project Directory

```bash
cd Iris-Dataset
```

### Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```text
Iris_dataset.ipynb
```

---

## Learning Outcomes

Through this project, the following concepts were practiced:

* Data Analysis
* Data Visualization
* Data Preprocessing
* Feature Scaling
* Classification Algorithms
* Model Evaluation
* Comparative Analysis of Machine Learning Models

---

## Future Improvements

* Hyperparameter Tuning
* Cross Validation
* Feature Selection Techniques
* Model Deployment using Flask or Streamlit
* Interactive Dashboard

---

## Author

Kousik Kar

Electronics and Telecommunication Engineering (ETCE)
Jadavpur University

---

⭐ If you found this project useful, consider giving the repository a star.

