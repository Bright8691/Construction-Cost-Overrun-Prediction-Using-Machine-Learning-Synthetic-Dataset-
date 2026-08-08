# Please still Underconstruction!!

# Construction Cost Overrun Prediction Using Machine Learning(with synthetic dataset)
# Project Overview
Cost overruns in construction projects is one of the most important challenges that affect construction industries. It is the major cause of budget inflation, profit lost and delay in projects. As a result, this project is meant to develop a machine learning regression model that will predict construction cost overruns before project completion, which enables project managers to make wise decisions and improve budget planning

This project followed an end-to-end industrial workflow which include the following, **data exploration, feature engineering, model development, evaluation, hyperparameter tuning, and business interpretation.**

The dataset is a synthetically generated set meant for educational and portfolio purposes.

# Business Objectives
The objectives of this project are:
1.	Construction cost overrun prediction using machine learning.
2.	Being able to Identify the major factors that contribute to budget increases.
3.	Compare multiple models.
4.	Evaluate and recommend the best model.
5.	Make recommendations to project managers and stakeholders based on the findings.

When there is a good prediction, it supports the actualization of any project construction and benefits the following:<br>
1. The clients (private, cooperatives or Government agencies)
2. The contractors  
3. The beneficiaries of the project
4. The community where the project is sited.

# Dataset Information
**Dataset Type: Synthetic**
The dataset contains following:
•	Project Type
•	Planned Budget ($ Millions)
•	Actual Cost ($ Millions)
•	Planned Duration
•	Actual Duration
•	Delay Months
•	Location Type
•	Primary Cause of Overrun
•	Cost Overrun ($ Millions)
•	Overrun Percentage

# Tools and Technologies
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Scikit-learn
•	Joblib
•	Jupyter Notebook
•	GitHub
•	Power BI

# Project Workflow

1. Business Understanding
- Defined the business problem.
- Established project objectives.
2. Data Understanding
- Loaded the dataset.
- Inspected data structure.
- Checked data types.
- Identified missing values.
- Removed duplicate records.
3. Exploratory Data Analysis (EDA)
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Distribution analysis
- Outlier detection
4. Data Pre-processing
- Feature engineering
- One-hot encoding
- Feature selection
- Train-test split
- Feature scaling
5. Machine Learning
The following regression algorithms were trained and evaluated:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
6. Model Optimisation
- Hyperparameter tuning using GridSearchCV
- Five-fold Cross Validation
7. Model Evaluation
Evaluation metrics include:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
8. Model Deployment
- Saved the best model using Joblib.
- Demonstrated prediction for new construction projects.

# Machine Learning Workflow

Load dataset<br>
		↓<br>
Understand Dataset<br>
		↓<br>
Data Cleaning<br>
		↓<br>
Exploratory Data Analysis<br>
		↓<br>
Feature Engineering<br>
		↓<br>
Encode Categorical Variables<br>
		↓<br>
Define Features & Target<br>
		↓<br>
Train-Test Split<br>
		↓<br>
Build Machine Learning Model<br>
		↓<br>
Model Evaluation<br>
		↓<br>
Model Diagonstics<br>
		↓<br>
Feature Importance<br>
		↓<br>
Cross-Validation<br>
		↓<br>
Save the Trained Model<br>
		↓<br>
Load Saved Model<br>
		↓<br>
Predict New Data<br>
		↓<br>
Power BI Dashboard<br>



**Models Developed**<br>

The following regression models were trained:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

**Model Performance**<br>


|  Model	                    |  MAE	   |  RMSE	   |  R²      |
|-----------------------------|----------|-----------|----------|
|  Linear Regression	        |  0.2200	 |   0.3246	 |   0.8645 |
|  Decision Tree	            |  0.1048	 |   0.1721	 |   0.9619 |
|  Random Forest	            |  0.0864	 |   0.1160	 |   0.9827 |
| Gradient Boosting Regressor |  3.63    |   22.95   |
***Best Model**<br>

Results
The machine learning models successfully predicted construction cost overruns using historical project characteristics.
The best-performing model achieved the strongest balance between prediction accuracy and generalisation, making it suitable for supporting project planning and budget risk assessment.

💡 Business Insights
The analysis highlights several important findings:
•	Longer project delays are associated with higher cost overruns.
•	Certain project types consistently exhibit greater budget risks.
•	Project duration and planning variables strongly influence final costs.
•	Feature importance analysis identifies the variables with the greatest impact on construction cost escalation.
These insights can support earlier intervention and more informed decision-making during project planning and execution.

📋 Recommendations
Based on the model results:
•	Improve project planning during the initiation phase.
•	Monitor projects with increasing schedule delays.
•	Strengthen contingency budgeting for high-risk projects.
•	Use predictive analytics as part of project monitoring.
•	Retrain the model regularly using updated project data.
📊 Power BI Dashboard
The interactive dashboard includes:
•	Executive KPIs
•	Total Planned Budget
•	Total Actual Cost
•	Total Cost Overrun
•	Average Cost Overrun
•	Average Delay
•	Cost Overrun by Project Type
•	Cost Overrun by Primary Cause
•	Planned Budget vs Actual Cost
•	Delay vs Cost Overrun
•	Interactive slicers


🚀 Future Improvements
Future work could include:
•	Incorporating real-world construction project data.
•	Testing advanced boosting algorithms such as XGBoost, LightGBM, and CatBoost.
•	Deploying the model using Streamlit or Flask.
•	Integrating the prediction model with Power BI for real-time decision support.



Emeka Egbuchulem
Civil Engineer | Data Analyst | Machine Learning Enthusiast
Skills
•	Python
•	SQL
•	Power BI
•	Microsoft Excel
•	Machine Learning
•	Data Visualisation

⭐ Acknowledgements
This project was developed as part of my machine learning portfolio to demonstrate practical applications of predictive analytics in construction project management.
The dataset is synthetic and was created solely for educational, research, and portfolio purposes.




