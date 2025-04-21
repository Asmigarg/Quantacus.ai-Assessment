# Email Marketing Campaign Optimization

This repository demonstrates how to optimize email marketing campaigns using machine learning. The goal is to predict and improve the click-through rate (CTR) of marketing emails by analyzing user data and email characteristics.

The project includes the following tasks:
1. **Data Preparation and Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Model Building**
4. **Model Evaluation**
5. **Optimization and Analysis**

## 📊 Project Overview

The marketing team of an e-commerce site has launched an email campaign. The goal of this project is to:
- Analyze how the email campaign performed (open rate and click rate).
- Build a predictive model to optimize email sending and maximize the probability of user clicks.
- Analyze different user segments to see how performance varies (e.g., by country, email version).
- Simulate A/B testing to estimate improvements in click-through rate (CTR).

## 🚀 Key Features

- **Modeling**: Uses machine learning models like `RandomForest`, `LogisticRegression`, and `XGBoost` to predict click-through rate (CTR).
- **Exploratory Data Analysis (EDA)**: Analyzes features like user country, email version, and sending hour to understand their impact on CTR.
- **Feature Importance**: Identifies the most influential features using `RandomForest`.
- **A/B Testing Simulation**: Simulates A/B testing to estimate CTR uplift.
- **Segmentation Analysis**: Evaluates performance by different segments (e.g., country, email version, sending time).
  
## ⚙️ Requirements

- Python 3.x
- pandas
- scikit-learn
- xgboost
- matplotlib
- seaborn

You can install the required dependencies using:

```bash
pip install -r requirements.txt
```

## 📂 Project Structure
```bash 
├── email_table.csv                # Data about emails sent
├── email_opened_table.csv         # Data on emails that were opened
├── link_clicked_table.csv         # Data on emails where the link was clicked
├── code.ipynb                     # Code to build and evaluate the model
├── requirements.txt               # Required dependencies
├── README.md                      # Project documentation
```

## 🧑‍💻 How to Contribute
Feel free to fork the repository and create pull requests. If you find any bugs or have suggestions for improvements, feel free to open an issue.
