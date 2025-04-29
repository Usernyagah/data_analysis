# 🌸 Iris Dataset Analysis and Visualization

This project demonstrates the process of data loading, cleaning, analysis, and visualization using the classic **Iris dataset**. The notebook is organized into three key tasks: data exploration, basic statistical analysis, and plotting various types of charts to uncover patterns in the dataset.

---

## 📁 Dataset
The dataset used is the [Iris dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-plants-dataset), directly loaded from `sklearn.datasets`.

- **Number of samples**: 150
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target**: Species (Setosa, Versicolor, Virginica)

---

## ✅ Tasks Overview

### 🔹 Task 1: Load and Explore the Dataset
- Load the Iris dataset using `sklearn.datasets.load_iris()`
- Display the first few rows using `.head()`
- Inspect data types and missing values
- Clean the data by removing any missing entries

### 🔹 Task 2: Basic Data Analysis
- Compute summary statistics (`mean`, `std`, etc.)
- Group by species and calculate mean of numerical features
- Identify notable trends or findings

### 🔹 Task 3: Data Visualization
Four types of customized plots are generated:

1. **Line Chart**  
   - Shows simulated trends in sepal and petal length over index.
2. **Bar Chart**  
   - Compares average petal length for each species.
3. **Histogram**  
   - Visualizes distribution of sepal width.
4. **Scatter Plot**  
   - Explores relationship between sepal length and petal length by species.

All plots are customized using **matplotlib** and **seaborn** with appropriate labels, titles, and legends.

---

## 📦 Requirements

To run this notebook, you need the following Python libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
