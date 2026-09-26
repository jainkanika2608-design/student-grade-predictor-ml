# Student Grade Predictor Using Machine Learning

## Overview

Student Grade Predictor is a beginner-level machine-learning project that predicts a student's final academic score using academic and study-related features.

The project uses Multiple Linear Regression as the primary prediction algorithm.

## Features

The model uses:

* Attendance percentage
* Assignment score
* Previous exam score
* Study hours
* Internal assessment score

The system predicts:

* Final score
* Project-defined grade
* Simple performance interpretation

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Machine Learning Algorithm

The project uses Multiple Linear Regression.

The dataset is divided into:

* 80% training data
* 20% testing data

A fixed random state of 42 is used for reproducibility.

## Dataset

The project generates a synthetic dataset containing 600 student records.

No external dataset is required.

The synthetic dataset is used only for educational demonstration and does not contain real student information.

## Input Features

| Feature             | Description                |
| ------------------- | -------------------------- |
| attendance          | Attendance percentage      |
| assignment_score    | Assignment average         |
| previous_exam_score | Previous examination score |
| study_hours         | Study hours per day        |
| internal_assessment | Internal assessment score  |

## Target

`final_score`

The final score is constrained between 0 and 100.

## Evaluation Metrics

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The exact results may be viewed directly in the notebook.

## Grade Classification

The project uses the following example thresholds:

| Score    | Grade |
| -------- | ----- |
| 90–100   | A+    |
| 80–89.99 | A     |
| 70–79.99 | B     |
| 60–69.99 | C     |
| 50–59.99 | D     |
| Below 50 | F     |

These are project-defined thresholds and should be changed according to an institution's official grading policy.

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. The dataset will be generated automatically.
4. The model will train automatically.
5. Evaluation metrics and graphs will be displayed.
6. At the interactive prediction section, enter student information.
7. The system will display the predicted score and grade.

## Project Structure

```text
Student Grade Predictor
│
├── Dataset Generation
├── Exploratory Data Analysis
├── Data Visualization
├── Feature Selection
├── Data Preprocessing
├── Train-Test Split
├── Linear Regression
├── Model Training
├── Prediction
├── Evaluation
├── Residual Analysis
├── Interactive Prediction
└── Grade Classification
```

## Limitations

The dataset is synthetic and the model is intentionally simple. Therefore, the results should not be interpreted as a real-world academic prediction system.

## Future Scope

Future improvements may include:

* Real educational datasets
* Additional student features
* Cross-validation
* Comparison of multiple algorithms
* Web application interface
* Database integration
* Model monitoring
* Fairness and reliability analysis

## Author

**Name:** Your Name
**Program:** B.Tech CSE – AI Specialization
**Semester:** 1st Semester

## License

This project is intended for educational and academic purposes.
