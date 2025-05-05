# 🌸 Iris Flower Classification - Machine Learning Project

This project uses machine learning to classify **Iris flowers** into one of three species:  
**Setosa**, **Versicolor**, or **Virginica**, based on measurements of their petals and sepals.

---

## 📌 Project Objective

Build a classification model using the **Iris dataset** to:
- Train a model on labeled flower data
- Predict flower species given measurements
- Evaluate the performance of the model

---

## 📊 Dataset Information

The dataset contains **150 samples** with 4 input features:

| Feature         | Description               |
|----------------|---------------------------|
| sepal length   | Length of the sepal (cm)  |
| sepal width    | Width of the sepal (cm)   |
| petal length   | Length of the petal (cm)  |
| petal width    | Width of the petal (cm)   |

**Target Variable**:  
- `species` — class label: `setosa`, `versicolor`, or `virginica`

---

## 🧰 Tools and Libraries Used

- **Python 3.x**
- **Pandas** – data handling
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – visualization
- **Scikit-learn (sklearn)** – ML models and metrics

---

## 🧠 Machine Learning Workflow

### 1. 📥 Load and Explore the Dataset
- Load the Iris dataset using `seaborn.load_dataset()`
- View basic info, structure, and statistical summary

### 2. 📊 Visualize the Data
- Use pair plots, heatmaps, and histograms to explore patterns and relationships between features

### 3. 📂 Split the Dataset
- Use `train_test_split()` from `sklearn.model_selection` to split data into training and test sets (80/20 split)

### 4. 🧪 Train the Model
- Train a **Logistic Regression** model using `sklearn.linear_model.LogisticRegression`

### 5. 📈 Evaluate the Model
- Use `accuracy_score`, `classification_report`, and `confusion_matrix` to evaluate predictions
- Visualize confusion matrix using Seaborn heatmap

---

## 📦 Installation

If not already installed, install dependencies with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
