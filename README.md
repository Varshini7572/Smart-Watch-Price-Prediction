# Smart Watch Price Prediction Project
This project focuses on predicting the prices of smart watches based on various features and specifications. The dataset used includes details such as brand, model, operating system, connectivity options, display characteristics, battery life, and more. The goal is to build a predictive model that can accurately estimate the price of a smart watch given its features.

## Project Steps
### 1. Import Necessary Libraries
Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn were utilized for data manipulation, visualization, and model building.

### 2. Import the Dataset
The dataset Smart watch prices.csv was imported using Pandas to begin the analysis.

### 3. Data Preparation
Handling Null Values: Missing data in the dataset was addressed by replacing null values in categorical columns with mode values and in numerical columns with mean values.
Encoding Categorical Values: Label Encoding was used to convert categorical columns into numeric form suitable for machine learning models.
Normalizing Data: The data was normalized where necessary, such as rounding off display sizes and standardizing battery life metrics.
### 4. Data Visualization
Exploratory data analysis (EDA) was performed using visualizations like heatmaps, pair plots, and bar plots to understand correlations between variables, distribution of features, and insights into top brands and operating systems.

### 5. Splitting Data into Train and Test Sets
The dataset was split into training and testing sets (80% training, 20% testing) to evaluate model performance.

### 6. Model Building
Several regression models were explored to predict smart watch prices:

#### Linear Regression
#### Decision Tree Regression
#### Random Forest Regression
#### Gradient Boosting Regression
#### XGBoost Regressor
 Each model was trained on the training set and evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

#### 7. Performance Metrics
Performance of each model was assessed and compared to determine the most effective model for price prediction based on the dataset.

#### 8. Saving the Best Model and Model Deployment
The best performing model was saved using pickle for future deployment or use.

#### 9. Web Interface Integration
An integrated web interface was developed to allow users to interact with the prediction model:

index.html: The homepage of the web application.

predict.html: A page for users to input smart watch features and get price predictions.

watch_prediction.html: A page that displays the predicted price of the smart watch based on user inputs.

The web interface uses Flask to handle form submissions and display results. Error handling and page navigation issues were addressed to ensure smooth user experience.

