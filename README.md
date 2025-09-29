# Project 2: Student Stress Classification

## Overview
This project explores whether machine learning models can classify **student stress levels** (low, moderate, high) using academic, personal, and social factors.  
The dataset comes from Kaggle’s **Student Stress Monitoring Dataset**, and the goal was to compare multiple classification algorithms to see which performs best.

## Models Used
- **Naive Bayes** – Simple, fast, works well with categorical-like data.  
- **K-Nearest Neighbors (KNN)** – Classifies by comparing to the closest data points.  
- **Support Vector Machine (SVM)** – Finds the best decision boundary between classes.  
- **Random Forest** – Ensemble of decision trees, handles complex data well.  

## Process
1. **Problem Definition** – Framed stress prediction as a classification problem.  
2. **Data Preprocessing** – Split features (`X`) and target (`y`), train/test split (80/20).  
3. **Exploratory Data Analysis** – Plotted stress distribution, correlation heatmap, and feature vs. stress comparisons.  
4. **Modeling** – Trained four classifiers and compared their performance.  
5. **Evaluation** – Measured accuracy, reviewed results, and discussed insights.  
6. **Storytelling & Conclusion** – Tied results back to the original question and discussed implications.  
7. **Impact** – Reflected on benefits and risks of stress prediction in education.  

## Results
- **Naive Bayes & SVM** achieved ~90% accuracy.  
- **KNN & Random Forest** followed closely at ~88%.  
- All models showed strong potential, but no single method was perfect.  

## Key Insights
- Stress levels can be predicted fairly well using survey-based factors like anxiety, self-esteem, academic performance, and social support.  
- Visualization showed clear patterns: higher anxiety and lower self-esteem linked to higher stress.  
- Machine learning could support student well-being, but fairness and ethical use must be considered.  

## Dataset
- [Student Stress Monitoring Dataset – Kaggle](https://www.kaggle.com/datasets/mdsultanulislamiovi/student-stress-monitoring-datasets)  

## References
- Brownlee, J. (2016). *Supervised Machine Learning Algorithms*. Machine Learning Mastery.  
  [Link](https://machinelearningmastery.com/supervised-learning-algorithms/)  

## How to Run
1. Clone the repo.  
2. Open `Project2FINAL.ipynb` in Jupyter Notebook or JupyterLab.  
3. Run the cells in order.  

---


