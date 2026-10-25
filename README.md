# 📊 BDAH & Machine Learning Practicals

> Hands-on learning in Big Data Analytics, Hadoop, and Machine Learning using Python.

## 📌 About the Repository

This repository brings together practical implementations for **Big Data Analytics and Hadoop (BDAH)** and **Machine Learning**.

The Machine Learning section contains seven practicals covering classification algorithms, optimization, and ensemble methods. Jupyter Notebooks are used to explore data, implement algorithms, and evaluate model performance.

## 🧪 Machine Learning Practicals

| No. | Practical | Key Learning |
| :---: | --- | --- |
| 1 | **Logistic Regression** | Predict categories using probabilities and a classification threshold. |
| 2 | **K-Nearest Neighbors (KNN)** | Classify observations based on their nearest neighbors. |
| 3 | **Support Vector Machine (SVM)** | Find a decision boundary that separates classes. |
| 4 | **Decision Tree** | Make predictions using interpretable decision rules. |
| 5 | **Random Forest** | Combine multiple decision trees to improve predictive performance. |
| 6 | **Gradient Descent** | Minimize a loss function through iterative parameter updates. |
| 7 | **Ensemble Techniques** | Combine models using approaches such as voting, bagging, and boosting. |

## 🛠️ Technologies & Libraries

| Tool / Library | Purpose |
| --- | --- |
| **Python** | Programming and algorithm implementation |
| **Jupyter Notebook** | Interactive coding and documentation |
| **NumPy** | Numerical computations |
| **Pandas** | Data loading, cleaning, and analysis |
| **Matplotlib & Seaborn** | Data visualization |
| **Scikit-learn** | Preprocessing, model training, and evaluation |
| **KaggleHub** | Downloading datasets in practicals that require it |

## 🎯 Objectives

- Understand the working principles of fundamental machine learning algorithms.
- Prepare datasets for model training and testing.
- Implement classification and optimization techniques.
- Evaluate models using appropriate performance metrics.
- Compare individual models with ensemble approaches.

## 🔄 Typical Workflow

1. **Load the dataset** and inspect its structure.
2. **Explore the data** using summaries and visualizations.
3. **Preprocess the features** and handle missing values where needed.
4. **Split the dataset** into training and testing sets.
5. **Fit preprocessing steps on training data** to prevent data leakage.
6. **Train the model** and generate predictions.
7. **Evaluate the results** and interpret model performance.

## 🚀 Getting Started

### 1. Download the Repository

Download the repository using **Code → Download ZIP**, then extract it.

Alternatively, clone it using Git with your repository URL.

### 2. Install the Required Libraries

Run the following command in your terminal or Anaconda Prompt:

```bash
python -m pip install numpy pandas matplotlib seaborn scikit-learn jupyter kagglehub
```

If you are installing directly from a Jupyter Notebook, use:

```python
%pip install numpy pandas matplotlib seaborn scikit-learn kagglehub
```

### 3. Launch Jupyter Notebook

Open a terminal in the project folder and run:

```bash
jupyter notebook
```

### 4. Run a Practical

Open a practical’s `.ipynb` file and execute its cells **from top to bottom**.

> **Note:** Check dataset paths before running each notebook. Practicals that download datasets through KaggleHub require an internet connection.

## 📈 Model Evaluation

Depending on the practical, classification models can be evaluated using:

| Metric | What It Measures |
| --- | --- |
| **Accuracy** | Overall proportion of correct predictions |
| **Precision** | How many predicted positives are actually positive |
| **Recall** | How many actual positives are correctly identified |
| **F1 Score** | Balance between precision and recall |
| **Confusion Matrix** | Correct and incorrect predictions for each class |
| **Log Loss** | Quality of predicted class probabilities |

## 📚 Learning Outcomes

After completing these practicals, learners should be able to:

- Explain and implement common machine learning algorithms.
- Prepare data for supervised learning.
- Train models and interpret their predictions.
- Select evaluation metrics suited to a classification problem.
- Recognize the importance of feature scaling and preventing data leakage.
- Compare models and explain their strengths and limitations.

## 👨‍💻 Author

**Yash Bambatkar**

Engineering student building practical skills in **Python, Data Analytics, and Machine Learning**.

---

⭐ If you find this repository useful, consider giving it a star!
