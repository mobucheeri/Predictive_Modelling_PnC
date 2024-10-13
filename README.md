# Predictive Modelling in Property and Casualty Insurance

This project focuses on developing predictive models for estimating claim severity within Property and Casualty insurance using machine learning techniques in Python. The models use data to predict loss severity and help insurers better assess risks.

## Project Structure:
- `main.py`: The main script to run the predictive models.
- `data/`: Directory for storing datasets.
- `models/`: Directory containing model scripts like decision tree and logistic regression.
- `scripts/`: Data processing and utility scripts.
- `notebooks/`: Jupyter notebooks for Exploratory Data Analysis (EDA).
- `requirements.txt`: File containing the required Python dependencies.

## Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/mobucheeri/Predictive_Modelling_PnC.git

  pip install -r requirements.txt

python main.py

This command runs the main script, which currently prints a welcome message. Future versions will include the implementation of the predictive models.

## Usage
To run the project:

1. Ensure the dataset is in the `data/` folder. You can download the dataset from [Allstate Claims Severity Dataset](https://www.kaggle.com/c/allstate-claims-severity/data).
2. After cloning the repository and installing the dependencies (as outlined above), you can run the project by executing the following command:
   ```bash
   python main.py

This command will:

- Load the dataset.
- Preprocess the data (e.g., handle missing values, scale features).
- Split the data into training and testing sets.
- Train a decision tree model on the training data.
- Evaluate the model on the test data, showing metrics like Mean Squared Error (MSE).


This command will:

Load the dataset.
Preprocess the data (e.g., handle missing values, scale features).
Split the data into training and testing sets.
Train a decision tree model on the training data.
Evaluate the model on the test data, showing metrics like Mean Squared Error (MSE).

## Dataset
Place the dataset in the data/ folder. You can use the Allstate Claims Severity Dataset or any other dataset with similar features.

The dataset should be in CSV format. Ensure that it has the necessary columns, including features and the target variable loss (or claim severity). The data_pipeline.py script will handle missing values and feature scaling.

## Models
This project uses the following machine learning models:

Decision Tree Regressor: A decision tree algorithm is used to predict the claim severity (continuous variable).

## Future implementations will include:
- Logistic Regression
- Random Forest
- Gradient Boosting
- Evaluation
- The model's performance is evaluated using the Mean Squared Error (MSE). This metric calculates the average squared difference between actual and predicted values, giving a sense of prediction accuracy.

## Future versions will include additional evaluation metrics like:

- R-squared (R²)
- Mean Absolute Error (MAE)

## Future Work
This project will expand to include:

- More advanced models such as Random Forest and Gradient Boosting.
- Hyperparameter tuning for improved accuracy.
- Feature importance analysis to understand which factors influence claim severity the most.
- Cross-validation for more robust model performance.

## Contributions
If you would like to contribute, please fork the repository and submit a pull request. Any contributions, whether improving code, fixing bugs, or adding new features, are welcome.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

