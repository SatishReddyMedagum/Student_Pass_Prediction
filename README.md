# Student_Pass_Prediction

# Student Pass Prediction Using Machine Learning

## 1. Project Title

Student Pass Prediction Using Machine Learning

## 2. Project Objective

The objective of this project is to develop a Machine Learning model to predict whether a student will pass or fail based on their academic performance.

The model uses study hours, attendance percentage, previous exam scores, and assignments completed to make predictions.

## 3. Dataset Details

- Dataset Name: `Besant_Student_Pass_Prediction.csv`
- Total Records: 200
- Total Columns: 5
- Input Features: 4
- Target Variable: Passed

| Feature               | Description                   |
| --------------------- | ----------------------------- |
| Study_Hours_Per_Day   | Daily study hours             |
| Attendance_Percentage | Student attendance percentage |
| Previous_Exam_Score   | Previous exam score           |
| Assignments_Completed | Completed assignments         |
| Passed                | 1 = Pass, 0 = Fail            |

## 4. Algorithm Used

Logistic Regression

Logistic Regression is a supervised Machine Learning classification algorithm used to predict categorical outcomes.

In this project, it predicts whether a student will pass or fail.

- Training Data: 80%
- Testing Data: 20%
- Random State: 42
- Stratification: Used to maintain class proportions.

## 5. Model Evaluation Results

The model performance is evaluated using the following metrics:

| Metric    | Result |
| --------- | ------ |
| Accuracy  | 82.50% |
| Precision | 85.71% |
| Recall    | 81.82% |
| F1-Score  | 83.72% |

## 6. Instructions to Run the Application

Prerequisites

- Python 3.13 or compatible version
- Visual Studio Code
- Required Python libraries

Step 1: Clone the Repository

```
git clone YOUR_GITHUB_REPOSITORY_LINK
```

Step 2: Navigate to the Project Folder

```
cd Student-Pass-Prediction
```

Step 3: Install Required Libraries

```
pip install -r requirements.txt
```

Step 4: Run the Application

```
streamlit run app.py
```

Step 5: Access the Application

Open the local URL displayed in the terminal to use the application.

## 7. GitHub Repository Link

Student Pass Prediction – GitHub Repository

## 8. Deployed Application Link

Student Pass Prediction – Live Application
