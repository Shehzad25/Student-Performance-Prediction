#🎓 Student Performance Prediction
📌 Project Overview

This project focuses on analyzing student academic and behavioral factors to predict their performance category (Grade A or B).
The goal is to understand how study habits, attendance, prior scores, and tutoring sessions influence student outcomes using machine learning classification techniques.

This is a basic data science project that emphasizes:

Exploratory Data Analysis (EDA)

Data preprocessing

Feature selection

Model training and evaluation

📂 Project Structure
Student-Performance-Prediction/
│
├── StudentPerformanceFactors.csv
├── Student_Performance_Prediction.ipynb
└── README.md

📊 Dataset Description

The dataset contains academic and behavioral information about students.

Key Features:

Hours_Studied – Average study hours per day

Attendance – Attendance percentage

Previous_Scores – Scores from previous exams

Tutoring_Sessions – Number of tutoring sessions attended

Exam_Score – Final exam score (used to derive performance category)

Target Variable:

Performance Category

Grade A → Exam Score ≥ 65

Grade B → Exam Score < 65

Note: The dataset does not contain failing students; therefore, the problem is framed as a performance classification task (A vs B) rather than pass/fail prediction.

🧪 Data Preprocessing

The following preprocessing steps were applied:

Handling missing values

Duplicate record checking

Outlier treatment using quantile capping

Encoding categorical variables

Feature scaling using StandardScaler

Feature selection based on correlation analysis

🤖 Machine Learning Models Used

Multiple classification algorithms were trained and evaluated:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Naive Bayes

Model performance was compared using accuracy score, and hyperparameter tuning was performed using GridSearchCV.

📈 Evaluation Metrics

Accuracy Score

Class distribution analysis

Correlation analysis

The final model selection was based on comparative performance across classifiers.

🧠 Key Insights

Attendance and previous academic performance are strong indicators of student outcomes.

The dataset is imbalanced, with more Grade B students than Grade A.

Reframing the problem to match real data distribution improves model reliability.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🎯 Learning Outcomes

Performed end-to-end exploratory data analysis

Built and evaluated multiple machine learning models

Applied realistic problem framing based on data characteristics

Gained hands-on experience with classification workflows

📌 Future Improvements

Handle class imbalance using techniques like SMOTE or class weighting

Add explainability (feature importance, SHAP)

Extend project with a web interface or API

Use cross-validation metrics beyond accuracy

👤 Author

Shehzad Khan
Aspiring Data Scientist

⭐ If you like this project, feel free to star the repository!
