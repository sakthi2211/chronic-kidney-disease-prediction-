🩺 Chronic Kidney Disease Prediction using Machine Learning and Explainable AI

📌 Project Overview

Chronic Kidney Disease (CKD) is a long-term medical condition that affects kidney function and can lead to serious health complications if not identified early.

This project aims to develop a Machine Learning-based classification system to predict the presence of Chronic Kidney Disease using clinical and diagnostic attributes.

The project incorporates data preprocessing, exploratory data analysis, feature selection techniques, multiple machine learning algorithms, and Explainable AI (XAI) to improve model interpretability.

🎯 Objectives

Develop a machine learning model for CKD prediction.

Perform data preprocessing and exploratory data analysis.

Identify important clinical features using feature selection techniques.

Compare multiple machine learning classification algorithms.

Evaluate model performance using standard classification metrics.

Interpret model predictions using SHAP (SHapley Additive exPlanations).

🛠️ Technologies Used

Category

Technologies

Programming Language

Python

Data Processing

Pandas, NumPy

Data Visualization

Matplotlib, Seaborn

Machine Learning

Scikit-learn

Feature Selection

Boruta

Explainable AI

SHAP

Development Environment

Jupyter Notebook / Google Colab

📂 Dataset

The project uses a Chronic Kidney Disease dataset containing clinical attributes associated with kidney health.

The dataset includes features related to:

Blood pressure

Specific gravity

Albumin

Sugar

Blood glucose

Blood urea

Serum creatinine

Hemoglobin

Packed cell volume

Hypertension

Diabetes mellitus

Other clinical indicators

Target Variable: CKD / Not CKD

Note: Update the dataset source, number of records, and feature count based on the actual dataset used.

⚙️ Project Workflow

Data Collection

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Feature Selection using Boruta

Model Training and Testing

Model Evaluation and Comparison

Explainable AI using SHAP

Result Analysis

🧹 Data Preprocessing

The following preprocessing steps are performed:

Handling missing values.

Removing duplicate records.

Encoding categorical variables.

Converting numerical attributes into appropriate data types.

Handling outliers where required.

Feature scaling where appropriate.

Splitting the dataset into training and testing sets.

🔍 Feature Selection

Boruta feature selection is used to identify relevant features and reduce unnecessary variables.

SHAP is also used to understand feature importance and analyze how individual clinical attributes contribute to model predictions.

🤖 Machine Learning Algorithms

The project explores and compares multiple classification algorithms:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

Other algorithms implemented in the project.

📊 Model Evaluation

The models are evaluated using:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Confusion Matrix

These metrics help assess classification performance and identify the most suitable model.

🧠 Explainable AI – SHAP

SHAP is used to interpret the predictions made by the selected machine learning model.

The explainability analysis includes:

Global feature importance.

SHAP summary plots.

Feature contribution analysis.

Individual prediction explanations.

This helps provide greater transparency into the factors influencing model predictions.

📈 Results

The performance of different machine learning algorithms is compared to identify the best-performing model.

Evaluation metrics and visualizations are available in the results/ directory.

Refer to the model comparison report and SHAP visualizations for detailed analysis.

🚀 Installation and Execution

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/Chronic-Kidney-Disease-Prediction.git

2. Navigate to the project directory

cd Chronic-Kidney-Disease-Prediction

3. Create a virtual environment

python -m venv venv

4. Activate the environment

Windows:

venv\Scripts\activate

Linux / macOS:

source venv/bin/activate

5. Install dependencies

pip install -r requirements.txt

6. Run the project

Open the Jupyter Notebook:

jupyter notebook

Navigate to the notebooks/ directory and execute the notebooks in the appropriate order.

🔮 Future Enhancements

Develop an interactive CKD prediction web application using Streamlit.

Integrate additional explainability techniques.

Perform hyperparameter optimization.

Explore ensemble learning approaches.

Improve model generalization using external validation datasets.

⚠️ Disclaimer

This project is developed for educational and research purposes only. Its predictions are not intended to replace professional medical advice, diagnosis, or treatment.

👨‍💻 Author

Sakthiraj

GitHub: https://github.com/sakthi2211
