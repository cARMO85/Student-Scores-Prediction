# Student Scores Prediction - Linear Regression Analysis

## Introduction
This project is part of my Data Science and Business Analytics Internship with The Sparks Foundation. The goal of this project is to analyze the relationship between the number of hours a student studies and the percentage of marks they score. We will use linear regression, a simple yet effective technique, to build a predictive model for student scores based on studying hours.

## Data Exploration and Preparation
To start the analysis, we load the data and explore its structure. The dataset consists of two columns: "Hours" and "Scores". Each row represents a student's number of study hours and the corresponding score they achieved.

### Data Visualization
To gain insights into the relationship between study hours and scores, we visualize the data using a scatter plot. The scatter plot allows us to visually inspect any potential linear relationship between study hours and scores.

### Data Splitting
Next, we split the data into input (study hours) and output (scores) variables. We reshape the input variable into a 2-dimensional array as required by scikit-learn's LinearRegression model.

## Model Training and Evaluation
We proceed to train a linear regression model on the data and evaluate its performance. The data is split into training and testing sets, with 80% used for training and 20% for testing. We create an instance of the LinearRegression model, fit it to the training data, and predict scores on the test data. We evaluate the model's performance using mean squared error (MSE) and R-squared (R2) score.

### Prediction
We use the trained model to predict the score for a student who studies for 9.25 hours per day.

## Conclusion
Based on our analysis and the linear regression model, if a student studies for 9.25 hours per day, we predict that their score would be approximately 92.39. This prediction is derived from the relationship observed between the number of hours studied and the scores achieved by the students in our dataset.

The analysis showed a strong positive correlation between the number of hours studied and the scores obtained. As the number of hours increased, the scores tended to rise as well. The model's performance evaluation indicated that it accurately captured the patterns and trends in the data, explaining approximately 97% of the variability in the scores.

However, it's important to note that individual student outcomes may vary due to various factors beyond study hours alone. Other factors such as individual learning abilities, motivation, and external influences can also impact a student's performance.

Overall, this analysis demonstrates the predictive power of the linear regression model in estimating scores based on study hours. It provides valuable insights into the relationship between study time and academic performance, emphasizing the importance of dedicating sufficient time to studying for achieving higher scores.

Feel free to explore the Jupyter Notebook to delve deeper into the analysis and modify it as per your requirements.

## Usage
1. Clone the repository to your local machine or download the project files.
2. Make sure you have the necessary dependencies installed: pandas, matplotlib, scikit-learn.
3. Open the Jupyter Notebook file (`.ipynb`) using Jupyter Notebook or JupyterLab.
4. Run the notebook cell by cell to see the step-by-step analysis and results.
5. Modify or add additional analysis as needed.

## License
This project is licensed under the [MIT License](LICENSE).

If you have any questions or suggestions, feel free to contact me. Happy learning!
