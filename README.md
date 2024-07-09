Stock Price Prediction Using Linear Regression This project uses Linear Regression to predict the closing prices of Google's stock based on the opening prices. The dataset used in this analysis is a CSV file containing historical stock prices. The project demonstrates data loading, preprocessing, model training, and evaluation using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

Requirements Python 3.x Pandas NumPy Matplotlib Seaborn Scikit-learn

Usage

Upload the Dataset First, upload the dataset CSV file containing the stock prices.

Load and Display the Data Read the uploaded CSV file into a Pandas DataFrame and display the first few rows and basic statistics of the dataset.

Check for Missing Values Check for any missing values in the dataset.

Prepare the Data for Training Select the 'Open' column as the feature (X) and the 'Close' column as the target variable (y).

Split the Data Split the data into training and testing sets.

Train the Model Train a Linear Regression model using the training data.

Make Predictions Use the trained model to make predictions on the test data.

Evaluate the Model Calculate the Mean Squared Error (MSE) and R-squared value to evaluate the model's performance.

Visualize the Results Plot the actual vs. predicted closing prices.
