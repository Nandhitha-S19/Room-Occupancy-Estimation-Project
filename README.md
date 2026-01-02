# Room-Occupancy-Estimation-Project
📌 Project Overview

This project focuses on predicting room occupancy using environmental and sensor data.
A complete machine learning pipeline is implemented, including data preprocessing, class imbalance handling, model training, and performance evaluation.

The objective is to classify whether a room is Occupied or Not Occupied based on sensor readings.

# 📂 Dataset Description
Dataset: Occupancy_Estimation.csv
Type: Sensor and environmental data
Target Variable: Occupancy
Features Include:
Temperature
Humidity
CO₂ levels
Light intensity
Other environmental parameters

#🔍 Project Workflow
1️⃣ Data Loading and Exploration
Loaded the dataset using Pandas
Examined dataset structure, data types, and null values
Checked the distribution of the target variable
Identified class imbalance in occupancy labels

2️⃣ Exploratory Data Analysis (EDA)
Analyzed feature relationships with room occupancy
Visualized data patterns using plots
Observed how environmental factors impact occupancy

3️⃣ Data Preprocessing
Separated features (X) and target (y)
Prepared data for machine learning models
Ensured consistency and cleanliness of input data

4️⃣ Train–Test Split
Split the dataset into:
Training set (80%)
Testing set (20%)
Used stratified sampling to preserve class distribution

5️⃣ Handling Class Imbalance
Applied SMOTE (Synthetic Minority Oversampling Technique) on training data
Balanced the dataset to avoid model bias toward the majority class

6️⃣ Model Training
Trained and compared multiple classification models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Models were trained using SMOTE-balanced data.

7️⃣ Model Evaluation
Evauated model performance using:
Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
Compared results across models to determine the best-performing classifier.

#📈 Key Observations
Environmental and sensor data are effective predictors of room occupancy
Handling class imbalance significantly improves model performance
Tree-based models performed better than linear models
The project demonstrates an end-to-end supervised ML workflow

🛠️ Technologies Used
Python
jupyter Notebook
Libraries:
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)

🚀 How to Run the Project
Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
Open Jupyter Notebook:
jupyter notebook
Run RoE.ipynb cell by cell to view the analysis.

🎯 Learning Outcomes
Built a complete machine learning classification pipeline
Gained experience in handling imbalanced datasets
Learned model comparison and evaluation techniques
Improved practical understanding of supervised learning

✍️ Author

Nandhitha
Student at University Of Madras | Aspiring Software Developer
