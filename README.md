# Employee Attrition Analysis
This repository hosts code for exploring the correlation between employee attrition and various attributes within a company's dataset. Leveraging scikit-learn's Decision Tree Classifier and GridSearchCV, this analysis aims to uncover patterns and factors contributing to employee turnover.
[The relationship between Attrition and Overtime work](https://work.chron.com/effects-improper-overtime-scheduling-employee-performance-4725.html) 

## Dataset
The dataset utilized in this analysis comprises detailed information about company employees, encompassing factors such as age, job role, department, tenure, etc. The target variable, 'Attrition', indicates whether an employee has departed from the company.

## Prerequisites
Python 3.10
**pandas**
scikit-learn
matplotlib
Ensure all necessary packages are installed using the following pip command:

### bash
Copy code
`pip install pandas scikit-learn matplotlib`
Usage
Clone this repository:
bash
Copy code
`git clone https://github.com/your_username/employee-attrition-analysis.git`
Navigate to the project directory:
bash
Copy code
`cd employee-attrition-analysis`
**Execute the Python script ipynb notebook*:
bash
Copy code

The script will load the dataset, preprocess the data, train a Decision Tree Classifier using GridSearchCV, and evaluate the model's performance.
File Structure
attrition_analysis.py: Python script containing code for data loading, preprocessing, model training, and evaluation.
README.md: This document providing an overview of the repository.
data/: Directory holding the dataset CSV file.
results/: Directory containing analysis outcomes such as plots and performance metrics.
Analysis Results
Upon executing the analysis script, you'll find the following results:

Confusion matrix
ROC curve
ROC AUC score
Visual representation of the Decision Tree
These outcomes offer insights into the model's performance and shed light on the relationship between employee attrition and other dataset variables.

Contributors
Your Name
Contributions to this repository are welcomed via forks and pull requests.

License
This project is licensed under the MIT License - refer to the LICENSE file for details.

