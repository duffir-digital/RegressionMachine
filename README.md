# RegressionMachine
Interactive Linear Regression Analyzer
This is an interactive web application built with Streamlit that allows users to perform both Simple and Multiple Linear Regression on their own data.

The tool provides a user-friendly interface to upload a dataset, select variables, train a model, and visualize the results, including an analysis of feature importance using backward elimination for multiple regression.
<img width="640" height="480" alt="Lab4_CSmith_TrainingSet" src="https://github.com/user-attachments/assets/59c406ce-e317-4c4c-b464-13808359ff24" />
# Features
Simple Linear Regression: Model the relationship between a single feature and a target variable.

Multiple Linear Regression: Analyze the relationship between multiple features and a target.

Interactive UI: Upload your own CSV and select columns with intuitive dropdowns.

Automatic Preprocessing: Handles one-hot encoding for categorical features in multiple regression.

Model Optimization: Includes a summary from statsmodels to demonstrate the concept of backward elimination for feature selection.

Instant Visualization: Generates and displays plots for training and test set results.
1. Prerequisites
Make sure you have Python 3.7+ installed.

2. Clone the Repository
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name

3. Install the Required Libraries
A requirements.txt file is included to make installation easy.

pip install -r requirements.txt

4. Run the Streamlit App

Once the dependencies are installed, run the following command in your terminal:

streamlit run app.py

I created this project inspired by some of my school assignments to help others in need of a regression tool.
