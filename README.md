<div align="center">

# ⚡ Data Analysis & Machine Learning Using Spark

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)](https://spark.apache.org)
[![SparkML](https://img.shields.io/badge/SparkML-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)](https://spark.apache.org/mllib/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)

A collection of **Jupyter Notebooks** covering core machine learning techniques — Regression, Classification, and Clustering — implemented using **Apache Spark's MLlib (SparkML)** for scalable, distributed data processing.

</div>

---

## 📁 Repository Structure

```
data-analysis-machine-learning-using-spark/
│
├── 📓 Regression_using_SparkML.ipynb        # Linear Regression with SparkML
├── 📓 Classification_using_SparkML.ipynb    # Logistic Regression / Tree Classifiers
├── 📓 Clustering_using_SparkML.ipynb        # K-Means Clustering
├── 📓 Airfoil Noise Prediction.ipynb        # End-to-end ML pipeline (regression)
└── 📓 FinalProject.ipynb                    # Capstone — full ML workflow
```

---

## 📒 Notebooks Overview

### 📈 Regression using SparkML
Predicts continuous outcomes using Spark's distributed regression algorithms.

- Built and trained a **Linear Regression** model using `pyspark.ml`
- Applied **feature engineering** with `VectorAssembler`
- Evaluated model performance using **RMSE** and **R² score**
- Used **Pipeline API** for clean, reproducible ML workflows

---

### 🔵 Classification using SparkML
Classifies data into categories using Spark-native classification algorithms.

- Implemented **Logistic Regression** and **Decision Tree** classifiers
- Applied **StringIndexer** and **OneHotEncoder** for categorical feature handling
- Evaluated using **accuracy**, **precision**, **recall**, and **F1-score**
- Used Spark **MulticlassClassificationEvaluator** and **BinaryClassificationEvaluator**

---

### 🔴 Clustering using SparkML
Groups unlabeled data into clusters using unsupervised learning.

- Applied **K-Means Clustering** using `pyspark.ml.clustering`
- Determined optimal clusters using the **Elbow Method** (WSSSE)
- Visualized cluster assignments and centroids
- Scaled features using **StandardScaler** before clustering

---

### ✈️ Airfoil Noise Prediction
An end-to-end ML pipeline predicting aerodynamic noise from NASA airfoil data.

- Loaded and explored the **NASA Airfoil Self-Noise dataset**
- Performed **EDA** and feature analysis with Spark DataFrames
- Built a full **ML Pipeline**: VectorAssembler → StandardScaler → LinearRegression
- Evaluated with **RMSE** and **R²**, and persisted the trained model

---

### 🏆 Final Project
A capstone notebook demonstrating a complete machine learning workflow from raw data to model evaluation using SparkML.

- End-to-end pipeline covering data loading, cleaning, feature engineering, model training, and evaluation
- Combines concepts from regression, classification, and data analysis notebooks

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Apache Spark** | Distributed data processing engine |
| **PySpark** | Python API for Spark |
| **SparkML (MLlib)** | Scalable machine learning library |
| **Spark SQL** | DataFrame operations and querying |
| **Jupyter Notebook** | Interactive development environment |
| **Python** | Core programming language |

---

## 🔑 Key SparkML Concepts Covered

| Concept | Used In |
|---|---|
| `VectorAssembler` | All notebooks — feature vector creation |
| `StandardScaler` | Airfoil, Clustering — feature normalization |
| `Pipeline` API | All notebooks — chaining stages |
| `LinearRegression` | Regression, Airfoil |
| `LogisticRegression` | Classification |
| `DecisionTreeClassifier` | Classification |
| `KMeans` | Clustering |
| `RegressionEvaluator` | Regression, Airfoil |
| `MulticlassClassificationEvaluator` | Classification |
| `StringIndexer / OneHotEncoder` | Classification — categorical encoding |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Apache Spark 3.x
- PySpark
- Jupyter Notebook

### 1. Clone the repository
```bash
git clone https://github.com/asadafridi567/data-analysis-machine-learning-using-spark.git
cd data-analysis-machine-learning-using-spark
```

### 2. Install dependencies
```bash
pip install pyspark jupyter pandas matplotlib seaborn
```

### 3. Launch Jupyter
```bash
jupyter notebook
```

### 4. Open any notebook and run all cells

> 💡 **Tip:** Run notebooks in order — Regression → Classification → Clustering → Airfoil → Final Project — for the best learning progression.

---

## 👨‍💻 Author

**Muhammad Asad** — Data Engineer & Python Developer

[![Email](https://img.shields.io/badge/Email-muasad007%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white)](mailto:muasad007@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-asadafridi567-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/asadafridi567)
[![EpubForge](https://img.shields.io/badge/Live%20Project-EpubForge-38BDF8?style=flat-square&logo=vercel&logoColor=white)](https://www.epubforge.com)
