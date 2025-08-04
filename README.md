# 📊 Health Insurance Cost Prediction using Linear Regression
This project focuses on predicting medical insurance costs using supervised machine learning, specifically Linear Regression. The dataset includes personal health and demographic information such as age, BMI, number of children, smoking status, and region, which are used to estimate the insurance premium.

# 📁 Project Structure
Linearregression(health_insurance_PRO).ipynb: Jupyter notebook containing the full code, EDA, preprocessing, model training, and evaluation.

# 📌 Objective
To analyze health insurance data and build a regression model that can accurately predict the insurance charges based on factors like:

Age

Sex

BMI

Number of Children

Smoking Status

Region

# 🧪 Tools & Technologies Used
Python

Pandas – Data handling

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine Learning (Linear Regression)

Jupyter Notebook

# 🔍 Exploratory Data Analysis (EDA)
The project performs detailed EDA to understand trends and relationships:

Distribution plots for numeric features

Box plots to explore outliers

Correlation heatmap

Comparison between smokers and non-smokers

Region-wise distribution

# 🔧 Preprocessing
Handled categorical data using label encoding and one-hot encoding.

Checked and handled null values if any.

Split data into features (X) and target (y).

Applied train-test split to evaluate model performance.

# 🤖 Model Building
Used Linear Regression from scikit-learn to predict charges.

Evaluated model with metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

# 📈 Results & Conclusion
The model shows a reasonable ability to predict insurance costs.

Smoking status and BMI significantly impact insurance charges.

Further improvement possible by applying advanced regressors like Ridge, Lasso, or XGBoost.

# ✅ Future Improvements
Include more real-world features (e.g., exercise habits, medical history).

Try advanced regression techniques for better accuracy.

Deploy the model using Streamlit or Flask for public interaction.

# 🔗 Dataset
Source: Kaggle – Medical Cost Personal Dataset 

