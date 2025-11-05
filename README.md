# ML_DMV

ML PRACTICALS
1. Feature Transformation
To use PCA Algorithm for dimensionality reduction. You have a dataset that includes measurements for diƯerent variables on wine (alcohol, ash, magnesium, and so on). Apply PCA algorithm & transform this data so that most variations in the measurements of the variables are captured by a small number of principal components so that it is easier to distinguish between red and white wine by inspecting these principal components.

2. Regression Analysis
Predict the price of the Uber ride from a given pickup point to the agreed drop-oƯ location. Perform following tasks: 1. Pre-process the dataset. 2. Identify outliers. 3. Check the correlation. 4. Implement linear regression and ridge, Lasso regression models. 5. Evaluate the models and compare their respective scores like R2, RMSE, etc.
Dataset link: https://www.kaggle.com/datasets/yasserh/uber-fares-dataset

3. Classification Analysis
Implement K-Nearest Neighbours’ algorithm on Social network ad dataset. Compute confusion matrix, accuracy, error rate, precision and recall on the given dataset.

4. Clustering Analysis
Implement K-Means clustering on Iris.csv dataset. Determine the number of clusters using the elbow method.

5. Ensemble Learning
Use diƯerent voting mechanism and Apply AdaBoost (Adaptive Boosting), Gradient Tree Boosting (GBM), XGBoost classification on Iris dataset and compare the performance of three models using diƯerent evaluation measures.

6. Reinforcement Learning
Implement Reinforcement Learning using an example of a maze environment that the agent needs to explore.


###DMV


DMV 1: Multi-format Sales Data Analysis
Load sales data from CSV, Excel, and JSON files, clean and merge them into a single DataFrame.Perform data cleaning, handle missing values, remove duplicates, and ensure consistent formats.  Analyze total sales, average order value, and top-selling products.
 Create visualizations (bar, pie, box plots) to show sales trends and insights.

DMV 2: Customer and Product Insights
Load customer, product, and transaction data from different file formats. Clean, transform, and merge datasets using common keys (e.g., Customer ID, Product ID). Compute total revenue per customer, identify top products, and segment customers by spending.  Visualize results using bar, pie, and box charts to show product performance and customer behavior.

DMV 3: Weather Data Analysis using OpenWeatherMap API
Use the OpenWeatherMap API to fetch real-time or historical weather data for a given city.
 Extract key parameters such as temperature, humidity, wind speed, and precipitation.
 Clean and preprocess the data, handle missing values, and analyze weather trends (average, max, min).  Visualize the results using line, bar, or scatter plots to show temperature changes and humidity trends over time.

DMV 4: Comparative Weather Visualization using Web API
Retrieve weather data from multiple cities using the OpenWeatherMap API.  Extract and clean attributes like temperature, pressure, and wind speed.  Aggregate data to compare cities by average temperature or wind speed.  Create visualizations (bar charts, heatmaps, or maps) to represent weather differences and correlations between attributes.

DMV 5: Customer Churn Data Cleaning
Import the "Telecom_Customer_Churn.csv" dataset. Perform data cleaning by handling missing values, removing duplicates, fixing inconsistent entries, and converting data types.  Detect and handle outliers, and perform feature engineering to create new relevant features.
 Normalize or scale the data and export the cleaned dataset for further analysis.

DMV 6: Preparing Telecom Data for Churn Prediction
Load and explore the Telecom Customer Churn dataset.  Clean the data by filling missing values, standardizing formats, and removing redundant records.  Perform data transformation (encoding, scaling, or normalization).  Create new derived features and split the data into training and testing sets for predictive modeling.

DMV 7: Real Estate Data Wrangling
Import the "RealEstate_Prices.csv" dataset and clean column names for consistency.
 Handle missing values, remove or impute where necessary, and encode categorical features.
 Filter data by property type or location, aggregate average prices by neighborhood, and handle outliers.  Prepare the cleaned and structured dataset for further analysis or modeling.

DMV 8: Housing Market Insights through Data Wrangling
Load and explore the real estate dataset.  Clean and standardize columns, handle missing data, and merge any additional datasets if available.  Filter records by time period or property type, encode categorical data, and compute summary statistics such as average and median prices.  Detect and treat outliers to prepare the dataset for predictive modeling.

DMV 9: AQI Trend Visualization
Import the "City_Air_Quality.csv" dataset and explore its structure.  Use Matplotlib to create line plots showing AQI trends over time and separate pollutant trends (PM2.5, PM10, CO).
 Add titles, labels, legends, and colors to make the plots clear and informative.

DMV 10: Pollutant Comparison and AQI Analysis
Load the air quality dataset and visualize pollutant-wise AQI comparisons using bar charts and box plots.  Use scatter or bubble plots to show the relationship between AQI and pollutant levels.  Customize your plots with appropriate axes labels, legends, and color themes to highlight key insights.

DMV 11: Regional Sales Performance Analysis
Import the "Retail_Sales_Data.csv" dataset and explore its structure.  Group the data by region to calculate total sales and identify top-performing regions.  Visualize sales distribution by region using bar or pie charts to highlight regional performance differences.

DMV 12: Sales Aggregation by Region and Product Category
Load the retail sales dataset and perform aggregation by both region and product category to find total sales for each combination.  Use stacked or grouped bar charts to compare regional sales across product categories and determine which categories perform best in each region.

DMV 13: Stock Price Trend Analysis
Import the "Stock_Prices.csv" dataset and convert the date column to a proper datetime format.  Visualize historical stock prices using line plots and calculate moving averages to identify long-term trends.  Analyze seasonal patterns and correlations between closing price and trading volume using suitable plots.

DMV 14: Stock Price Forecasting
Load and explore the stock price dataset for a given company.  Prepare the data for time series modeling by formatting dates and handling missing values.  Use ARIMA or exponential smoothing models to forecast future stock prices and visualize actual vs. predicted trends using line charts.
