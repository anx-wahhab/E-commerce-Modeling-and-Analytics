# E-commerce Modeling and Analytics

This repository contains the code and analysis for leveraging web analytics and predictive modeling techniques to improve decision-making for an e-commerce company. Using a dataset of 12,330 customer sessions, we explore customer behavior, build predictive models, and provide actionable insights to enhance marketing efforts and increase revenue.

## Dataset
- **Customer Sessions**: The dataset includes various attributes such as customer browsing behavior, time spent on different pages, bounce rates, and special event proximity.
- **Target Variable**: Revenue (True/False) indicating whether a purchase was made during the session.

## Project Structure
1. **Data Analysis**: Exploratory data analysis and visualization to uncover customer behavior patterns.
2. **Predictive Modelling**:
    - **Random Forest**: Achieved high accuracy in predicting customer purchase likelihood.
    - **Logistic Regression**: Provided additional insights for binary classification.
3. **Clustering**: K-Means clustering to segment customers based on their session behavior for targeted marketing.

### Results
- **Random Forest Accuracy**: 90%
- **Logistic Regression Accuracy**: Comparable performance in classifying purchase behavior.

## Tools & Libraries
- **Python**: The project was implemented in Python, using libraries like:
    - `pandas`, `matplotlib`, `seaborn`, `scikit-learn` for data analysis and visualization.
    - `RandomForestClassifier` and `LogisticRegression` for predictive modeling.

## Report
A detailed PDF report of the analysis can be found [here](./Report.pdf), which includes methodologies, results, and recommendations for the e-commerce company.

## How to Use
1. Clone the repository.
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the `script.ipynb` notebook to replicate the analysis.