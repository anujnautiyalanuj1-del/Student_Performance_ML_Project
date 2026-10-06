# Student Performance Prediction using Machine Learning

## Project Overview
This is a beginner-friendly AI/ML project that predicts whether a student is likely to PASS or FAIL using student performance factors.

## Inputs
- Study hours per day
- Attendance percentage
- Previous marks
- Assignment score
- Internal exam marks
- Sleep hours per day

## Machine Learning Algorithm
Logistic Regression is used for binary classification:
- 1 = PASS
- 0 = FAIL

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib

## How to Run

### 1. Open the project folder in VS Code
Open a terminal in the `Student_Performance_ML` folder.

### 2. Install libraries
```bash
pip install -r requirements.txt
```

### 3. Train the model
```bash
python train_model.py
```

This creates:
`model/model.pkl`

### 4. Start the web application
```bash
streamlit run app.py
```

A browser window will open automatically.

## Project Flow
Student Data → Preprocessing → Logistic Regression → Prediction → Probability → Result

## Important
The included dataset is a small educational sample created for demonstration. It should not be used for real academic decisions.
