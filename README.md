# Student Performance Prediction - Pass/Fail Classification

**Author:** GUTTI BHARGAVI  
**Project Type:** Machine Learning - Classification  
**Tools & Libraries:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

---

## Project Overview

This project aims to predict whether a student will **pass or fail** based on their study hours, attendance percentage, and previous exam scores using a Logistic Regression classification model.

---

## Dataset

The dataset contains the following features for each student:

- `study_hours`: Number of hours spent studying  
- `attendance`: Attendance percentage  
- `previous_score`: Previous exam score  
- `final_score`: Final exam score (used to create the pass/fail label)  

The `pass_fail` column is derived from `final_score`:
- **Pass:** final_score >= 50  
- **Fail:** final_score < 50  

---

## How to Run

1. Clone or download this repository.  
2. Make sure you have Python 3 installed.  
3. Install required packages using:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook `student_preprocessing.ipynb` in Jupyter Notebook or JupyterLab.  
5. Run all cells step-by-step to load data, clean it, create pass/fail labels, and visualize the data.

---

## Project Features

- Data cleaning and handling missing values  
- Creating a binary classification label (Pass/Fail)  
- Exploratory data analysis with pair plots and heatmaps  
- Logistic Regression model to classify student outcomes  
- Model evaluation with accuracy, confusion matrix, and classification report  

---

## Results

- Model accuracy is displayed after training.  
- Confusion matrix and classification report provide detailed insights into performance.  
- Example prediction on a sample student shows how to use the trained model.

---

## Folder Structure

