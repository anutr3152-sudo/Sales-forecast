# 📊 Lenskart Historical Sales Analysis & Prediction

## 📌 Project Overview

This project focuses on analyzing **Lenskart historical sales data** using Data Preprocessing, Exploratory Data Analysis (EDA), Feature Engineering, Machine Learning, and Data Visualization.

The main objective is to understand historical sales patterns and build a Machine Learning model to predict sales-related outcomes based on the available historical data.

---

## 🎯 Objectives

- Analyze historical Lenskart sales data.
- Clean and preprocess the dataset.
- Handle missing and duplicate values.
- Perform Exploratory Data Analysis (EDA).
- Identify important sales patterns and relationships.
- Apply feature engineering techniques.
- Train a Machine Learning classification model.
- Evaluate the model using Accuracy, Precision, Recall, and F1 Score.
- Visualize model performance using a Confusion Matrix.
- Compare actual and predicted results.

---

## 🗂️ Project Workflow

```text
Raw Sales Dataset
       ↓
Data Cleaning
       ↓
Data Preprocessing
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Train-Test Split
       ↓
Machine Learning Model
       ↓
Prediction
       ↓
Model Evaluation
       ↓
Visualization

Sales-forecast/
│
├── data/
│   ├── raw/
│   │   └── sales_data.csv
│   │
│   └── processed/
│       └── cleaned_sales_data.csv
│
├── notebooks/
│   ├── preprocessing.ipynb
│   └── model_train.ipynb
│
├── README.md
└── requirements.txt

Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Development Tools
Jupyter Notebook
Visual Studio Code
Git
GitHub
🔧 Data Preprocessing
The following preprocessing techniques were performed:
Handling missing values
Removing duplicate records
Data type conversion
Encoding categorical variables
Feature selection
Feature scaling/normalization
Preparing data for Machine Learning
📊 Exploratory Data Analysis
EDA was performed to understand the historical sales dataset.
Visualizations
The project includes visualizations such as:
Sales distribution
Feature relationships
Scatter plots
Correlation analysis
Outlier detection
Model performance visualization
🤖 Machine Learning
A Machine Learning classification approach was implemented to predict the target sales outcome.
Model
Logistic Regression
The dataset was divided into training and testing sets before model training.
X_train, X_test, y_train, y_test = train_test_split(
    X, y,
    test_size=0.2,
    random_state=42
)
The trained model was then used to generate predictions on the test dataset.
📈 Model Evaluation
The model was evaluated using:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
📊 Model Performance
Metric
Score
Accuracy
~92%
Precision
~92%
Recall
~92%
F1 Score
~92%
These results indicate that the model provides good predictive performance on the test dataset.
🔲 Confusion Matrix
The confusion matrix is used to evaluate the classification model by comparing the actual values with the predicted values.
[[13773  1227]
 [ 1179 13821]]
The visualization helps identify:
True Positives
True Negatives
False Positives
False Negatives
📉 Visualization
The project uses visualization techniques to make the results easier to understand.
Model Performance
The Accuracy, Precision, Recall, and F1 Score are represented using a bar chart.
Confusion Matrix
A Seaborn heatmap is used to visualize the confusion matrix.
Actual vs Predicted
Actual and predicted values are plotted to understand the model's prediction performance.
💡 Key Insights
Historical sales data can be used to identify useful sales patterns.
Data preprocessing is important for improving Machine Learning performance.
Feature engineering helps the model learn meaningful patterns.
The implemented model achieved approximately 92% performance across the main evaluation metrics.
Visualization makes the model results easier to interpret.
🚀 Future Enhancements
Future improvements can include:
Implementing advanced Machine Learning algorithms.
Comparing multiple models.
Using time-series forecasting techniques for future sales prediction.
Adding dynamic pricing recommendations.
Building an interactive dashboard using Streamlit or Power BI.
Deploying the trained model as a web application.
Integrating real-time sales data.
👩‍💻 Author
T. R. Anu
BE – Artificial Intelligence and Machine Learning
⭐ Project Highlights
✔ Historical Sales Data Analysis
✔ Data Preprocessing
✔ Exploratory Data Analysis
✔ Feature Engineering
✔ Machine Learning
✔ Model Evaluation
✔ Confusion Matrix
✔ Data Visualization
📌 Conclusion
The Lenskart Historical Sales Analysis & Prediction project demonstrates how historical sales data can be processed, analyzed, visualized, and used for Machine Learning-based prediction.
The project provides a complete workflow from raw data preprocessing to Machine Learning model evaluation, making it useful for understanding real-world sales analytics and predictive modeling.

