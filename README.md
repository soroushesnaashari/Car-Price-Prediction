## Car Price Prediction Using Machine Learning

### Overview

This project aims to predict the selling price of used cars based on various features such as car age, mileage, fuel type, transmission type, and more. The model is built using machine learning techniques, specifically Linear Regression and optimized with Ridge Regression to improve prediction accuracy. The dataset includes car attributes such as present price, fuel type, number of kilometers driven, and seller type, which are used to predict the car's selling price.
The project showcases the complete data processing pipeline, from feature engineering and scaling to model evaluation and prediction. It provides insights into how different factors influence car pricing in the market.

<br>

### Process Workflow

1. **Data Collection & Cleaning:** <br>
    - The dataset is pre-processed by replacing categorical variables (like fuel type, seller type, and transmission) with numerical representations.
    - The car's age is derived from the year of manufacture to better represent the condition of the car.

2. **Feature Engineering:** <br>
    - Additional features are considered, such as creating interaction terms, to capture the relationship between variables that can better predict the selling price.
    - Scaling is performed using StandardScaler and MinMaxScaler to normalize the features for improved model performance.

3. **Model Building:** <br>
  The initial model is trained using Linear Regression to predict the car's selling price.

4. **Model Evaluation:** <br>
    - Performance metrics, including *Mean Absolute Error (MAE)*, *Mean Squared Error (MSE)*, *Root Mean Squared Error (RMSE)* and *R² Score*, are used to evaluate the model’s accuracy.
    - The trained model is applied to test data to compare actual and predicted selling prices.

5. **Results:** <br>
  The final model provides predictions that closely match the actual values, though further fine-tuning can improve performance. The results are stored and can be analyzed to understand which features have the most significant     impact on pricing predictions.

<br>

### Results

The linear regression model provides the following performance metrics:

- **Mean Absolute Error (MAE)**: Represents the average absolute difference between the predicted and actual selling prices.
- **Mean Squared Error (MSE)**: Measures the average of the squared differences between predicted and actual prices.
- **Root Mean Squared Error (RMSE)**: The square root of MSE, giving the error magnitude in the original scale.
- **R² Score**: The coefficient of determination, indicating how well the model's predictions match the true values. <br>
While the model shows a reasonable degree of accuracy, there is potential for improvement by using more complex models like **Random Forest** which was not effective

<br>

### Repository Contents

- **Data:** Contains the [Original Dataset](https://www.kaggle.com/datasets/janagamamanojkumar/car-dekho) and you can see the cleaned dataset in notebook.

- **Notebook:** The main script containing the machine learning pipeline, from data processing to model evaluation.

- **README.md:** Documentation that provides an overview of the project, workflow and results.

<br>

### How to Contribute
Contributions are welcome! If you'd like to improve the project or add new features:

1. **Fork the repository.**
2. **Create a new branch.**
3. **Make your changes and submit a pull request.**
