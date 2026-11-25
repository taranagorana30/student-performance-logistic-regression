# Student Performance Prediction using Logistic Regression

## Project Overview

This project predicts student performance based on the number of study hours using three types of Logistic Regression:

1. Binary Logistic Regression
2. Multinomial Logistic Regression
3. Ordinal Logistic Regression

The project is developed using Python and includes an attractive Tkinter GUI for entering student details and viewing prediction results.

## Features

- Student name input
- Study hours input
- Binary Logistic Regression prediction (Pass/Fail)
- Multinomial Logistic Regression prediction (Low/Medium/High)
- Ordinal Logistic Regression prediction (Poor/Average/Good/Excellent)
- Interactive Tkinter desktop application
- Graph visualization for all three Logistic Regression models
- Input validation
- Clear form functionality

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Tkinter

## Project Structure

```text
student-performance-logistic-regression/
│
├── student_prediction.py
├── README.md
└── requirements.txt
```

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/student-performance-logistic-regression.git
```

### Step 2: Open the Project Folder

```bash
cd student-performance-logistic-regression
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run the Project

```bash
python student_prediction.py
```

## How to Use

1. Run the Python application.
2. Enter the student's name.
3. Enter study hours between 1 and 12.
4. Click the Predict button.
5. View the predictions from all three Logistic Regression models.
6. Click Show Graphs to view the probability graphs.
7. Click Clear to reset the form.

## Machine Learning Models

### Binary Logistic Regression

Predicts whether a student will Pass or Fail.

### Multinomial Logistic Regression

Predicts student performance into three categories:

- Low
- Medium
- High

### Ordinal Logistic Regression

Predicts student performance into ordered categories:

- Poor
- Average
- Good
- Excellent

## Graph Visualization

The project displays three graphs:

- Binary Logistic Regression probability curve
- Multinomial Logistic Regression probability curves
- Ordinal Logistic Regression probability curves

These graphs help understand how predicted probabilities change with study hours.

## Learning Objectives

- Understand different types of Logistic Regression.
- Train machine learning models using Scikit-learn.
- Implement Ordinal Logistic Regression using Statsmodels.
- Make predictions for new data.
- Visualize prediction probabilities using Matplotlib.
- Build a desktop GUI using Tkinter.

## Important Note

This project uses a small sample dataset created for educational purposes. Predictions are intended for learning and demonstration only and should not be used for actual academic decisions.

## Author

Created as a Python Machine Learning learning project.
