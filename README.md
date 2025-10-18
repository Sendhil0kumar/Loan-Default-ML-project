# Loan Default Prediction Project  Loan Default Prediction Project 📊

This project uses a dataset from Kaggle to predict whether a loan applicant will default. It covers the complete machine learning workflow from data cleaning and exploratory data analysis (EDA) to building and evaluating predictive models.

## Key Findings from the Baseline Model

* **Initial Analysis:** The dataset was highly imbalanced, with defaults making up only ~25% of the cases.
* **Model Performance:** A baseline Logistic Regression model achieved 87% accuracy but had a poor recall of 53% for default cases.
* **Overfitting:** A Decision Tree model achieved a perfect but unrealistic 100% accuracy, highlighting a classic case of overfitting and the need for more robust models.

## Project Structure

* **/data**: Contains the raw CSV dataset.
* **/notebooks**: Contains the Jupyter Notebooks.
    * `01_Baseline_Model.ipynb`: Covers initial EDA, data cleaning, and the creation of our first baseline models.
    * `02_Improved_Model.ipynb` (Coming Soon): Will focus on advanced techniques like SMOTE for imbalance, Random Forest modeling, and cross-validation to improve performance.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
