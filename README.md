# Loan Default Prediction Project 📊

This project uses a Kaggle dataset to predict loan defaults. It documents a complete, end-to-end machine learning workflow, from initial data analysis to advanced modeling and, most importantly, critical diagnostic investigation.

## Project Outcome: A Data Diagnostics Case Study

The final outcome of this project was not a deployable predictive model, but a thorough investigation and diagnosis of a flawed dataset. The key finding was the presence of severe **data leakage**, where features in the dataset contained information about the final loan status, making a realistic prediction impossible.

This project demonstrates a professional data science workflow where identifying data quality issues is a primary and critical task.

## Summary of Findings

* **Baseline Model:** An initial Logistic Regression model achieved 87% accuracy but had a poor recall of 53% for default cases, highlighting the risk of relying on accuracy alone with imbalanced data.
* **Overfitting Identified:** A simple Decision Tree model achieved a perfect but unrealistic 100% accuracy, providing a classic example of overfitting.
* **Data Leakage Confirmed:** Even after applying advanced techniques like SMOTE and a Random Forest model, the near-perfect scores persisted. This confirmed that the dataset itself is fundamentally flawed with data leakage, rendering it unsuitable for a real-world predictive task.

## Project Structure

* **/data**: Contains the raw CSV dataset.
* **/notebooks**: Contains the Jupyter Notebooks detailing the project's progression.
    * `01_Baseline_Model.ipynb`: Covers initial EDA, data cleaning, and the creation of our first baseline models.
    * `02_Improved_Model.ipynb`: Implements advanced techniques and concludes with the final diagnosis of data leakage.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
