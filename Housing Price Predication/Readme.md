<h1>Housing Price Prediction Portfolio</h1>

<h2>Introduction</h2>

In this portfolio, I will demonstrate a step-by-step approach to building a housing price prediction model using machine learning techniques.
I will explain each step, provide code snippets, and discuss the rationale behind my decisions.

<h2>Project Overview</h2>

The goal of this project is to create a model that predicts housing prices based on various features like area, number of bedrooms, bathrooms, 
and more. Accurate price predictions are crucial for buyers, sellers, and real estate professionals.

<h2>Step 1: Data Collection and Exploration</h2>
In these step I imported necessary libraries and loaded the housing dataset.
Performed basic data exploration by displaying the first few rows, data info, shape, and columns.
Checked for duplicates and missing values in the dataset.
Utilized visualizations such as pair plots, correlation heatmaps, and distribution plots to gain insights into the data.

<h2>Step 2: Data Preprocessing</h2>
In these step Calculated descriptive statistics to understand the data's central tendency and dispersion.
then we identified and removed duplicate rows. After that we checked and handled missing values in the dataset.

<h2>Step 3: Data Visualization and Analysis</h2>
Created visualizations to understand the relationships between variables.
Plotted pair plots, correlation heatmaps, distribution plots, and count plots for selected features.

<h2>Step 4: Encoding</h2>
In these step first I identified binary and ordinal variables in the dataset. After that I applied one-hot encoding to binary variables using OneHotEncoder.
and then applied label encoding to the ordinal variable 'furnishingstatus'.

<h2>Step 5: Outlier Detection</h2>
Inthese step I was try to find outliers and handling them. Utilized box plots and the IQR method to detect and handle outliers in the 'price' and 'area' columns Outliers 
can significantly affect model performance, so they need to be addressed.

<h2>Step 6: Data Splitting and Scaling</h2>
Split the data into training and testing sets using train_test_split.
Applied feature scaling using StandardScaler to standardize the feature values.

<h2>Step 7: Model Building and Evaluation</h2>
In these step we choose a variety of regression models to evaluate, such as Linear Regression, Decision Tree Regression, Random Forest Regression, Ridge, Lasso, Gradient Boosting Regression, 
and Support Vector Regression (SVR). For each model: Fit the model on the training data. Make predictions on the test data. 
Calculate and display evaluation metrics: Mean Squared Error (MSE) and R-squared (R2).

<h2>Step 8: Model Deployment</h2>
Saved the best-performing Linear Regression model using joblib for future predictions.

<h2>Step 9: User Input and Prediction</h2>
Defined a function to get user inputs for various features related to a house.
Encoded binary inputs and created a user DataFrame.
Utilized the pre-trained Linear Regression model to predict the housing price based on user inputs.
Displayed the predicted price to the user.

<h2>Conclusion</h2>
In this project portfolio, I've demonstrated the entire process of building a housing price prediction model. I've covered data collection, preprocessing, visualization, 
outlier handling, feature scaling, model building, evaluation, and optional deployment. Accurate housing price predictions can be valuable for various stakeholders in the real estate industry.
And then predicts the housing price based on the user's input.
