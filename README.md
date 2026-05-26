# Placement Prediction Model with Logistic Regression

## Project Description
This project uses a simple placement prediction model using Logistic Regression. The model aims to predict whether a student will be placed based on their academic performance metrics (CGPA and IQ).

## Data
The dataset used for this project is `Placement.csv`, which contains student information including `Student_ID`, `CGPA`, `IQ`, and `Placement` status (0 for Not Placed, 1 for Placed).

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `sklearn`: For machine learning functionalities, including model selection (train-test split), logistic regression, and accuracy metrics.
- `matplotlib.pyplot`: For creating static and interactive visualizations.
- `seaborn`: For making informative statistical graphics.

## Model Implementation
1.  **Data Loading and Cleaning**: The `Placement.csv` file is loaded into a pandas DataFrame. Rows with missing values are dropped to ensure data quality.
2.  **Feature Selection**: 'CGPA' and 'IQ' are selected as features (`X`), and 'Placement' is set as the target variable (`y`).
3.  **Train-Test Split**: The data is split into training and testing sets (80% training, 20% testing) to evaluate the model's performance on unseen data.
4.  **Model Training**: A Logistic Regression model from `sklearn.linear_model` is initialized and trained on the training data.
5.  **Prediction and Evaluation**: The trained model makes predictions on the test set, and the accuracy of these predictions is calculated.

## Results
The Logistic Regression model achieved a test accuracy of **85.00%**, indicating its effectiveness in predicting student placement based on the given features.

## Visualization
The project includes a scatter plot visualizing the relationship between CGPA and Placement Status, with a logistic regression line overlaid to show the trend.

---

<img width="898" height="547" alt="image" src="https://github.com/user-attachments/assets/453c6210-bf79-4f1e-a018-a82f53219c54" />
