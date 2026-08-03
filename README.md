# 🏥 Medical Insurance Cost Prediction

## Capstone Project – CareCast Team

## Project Overview

Healthcare insurance companies need accurate methods for estimating medical expenses to improve premium pricing, risk assessment, and financial planning. This project develops a machine learning regression model that predicts individual healthcare insurance charges based on demographic and lifestyle characteristics.

Using Exploratory Data Analysis (EDA) and multiple regression algorithms, the project identifies the key factors influencing insurance costs and selects the best-performing predictive model.



## Business Problem

Healthcare expenses vary significantly among individuals due to factors such as age, body mass index (BMI), smoking habits, family size, sex, and geographical region.

The objective of this project is to:

* Explore the dataset to understand factors influencing medical insurance charges.
* Build and compare multiple regression models.
* Identify the best-performing model.
* Provide business recommendations for healthcare insurance pricing and risk assessment.



## 📂 Dataset

**Dataset Source:** Kaggle – Medical Cost Personal Dataset

**Dataset Link:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

### Features

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the primary beneficiary              |
| sex      | Gender                                      |
| bmi      | Body Mass Index                             |
| children | Number of dependents                        |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (Target Variable) |



## 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib



## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Data inspection
* Missing value analysis
* Duplicate detection
* Descriptive statistics
* Distribution of numerical variables
* Distribution of categorical variables
* Correlation analysis
* Relationship between features and insurance charges
* Outlier detection

### Key Insights

* Smoking status has the strongest influence on insurance charges.
* Older individuals generally incur higher healthcare expenses.
* Higher BMI is associated with increased medical costs.
* Region has relatively little effect on insurance charges.
* Healthcare charges are highly right-skewed with genuine high-cost outliers.



## 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Extra Trees Regressor
* Gradient Boosting Regressor

Models were compared using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score
* Cross-validation



## 📈 Model Evaluation

The best-performing model was selected based on:

* Highest R² Score
* Lowest MAE
* Lowest RMSE

Additional evaluation included:

* Actual vs Predicted plot
* Residual analysis
* Feature importance analysis



## 💡 Business Recommendations

Based on the analysis:

* Incorporate smoking status into premium pricing strategies.
* Encourage preventive healthcare programs to reduce long-term medical costs.
* Use predictive analytics for personalized insurance plans.
* Improve financial planning through accurate healthcare cost estimation.
* Support data-driven underwriting and pricing decisions.



## 📁 Project Structure

```
Medical-Insurance-Cost-Prediction/
│
├── data/
│   └── insurance.csv
│
├── notebooks/
│   └── Carecast_Team.ipynb
│
├── models/
│   ├── best_insurance_model.pkl
│   ├── standard_scaler.pkl
│   └── label_encoder.pkl
│
├── results/
│   └── model_performance.csv
│
├── README.md
└── requirements.txt




## 🚀 How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Navigate to the project directory.

```bash
cd your-repository
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the notebook and run all cells.


## 👥 CareCast Team

This capstone project was completed collaboratively by the **CareCast Team**, with each member contributing to a specific stage of the machine learning workflow.

| Team Member                     | Role                         |
| ------------------------------- | ---------------------------- |
| **Onyekanle Celestina Chinedu** | Team Leader                  |
| **Emmanuel**                    | Data Cleaning                |
| **Adeniyi**                     | Exploratory Data Analysis    |
| **Imadon**                      | Exploratory Data Analysis    |
| **Favour Awofiranye**           | Feature Engineering          |
| **Adeniran**                    | Linear Regression Models     |
| **Geoffrey**                    | Tree-Based Models            |
| **Hannat**                      | Model Evaluation             |
| **Israel**                      | Documentation & Slides       |


### Team Responsibilities

The project was developed using a collaborative workflow in which each member was responsible for a specific phase of the data science lifecycle, including data preparation, exploratory data analysis, feature engineering, model development, evaluation, documentation, and presentation. This division of responsibilities ensured efficient teamwork while maintaining consistency and quality throughout the project.



Project developed as part of a Data Science Capstone Project.



## 📄 License

This project is intended for educational purposes.
