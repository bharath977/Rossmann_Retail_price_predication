# Rossmann_Retail_price_predication
The Rossmann Retail Price Prediction project aims to develop an effective machine learning model that accurately predicts the sales of products at Rossmann, a leading drugstore chain. By leveraging historical sales data, along with external factors such as promotional activities, holidays, and store information, the model will provide valuable insights to assist Rossmann in optimizing their pricing strategies and driving business growth.

The project begins with data collection, where extensive historical sales data from various Rossmann stores across different regions is gathered. Additionally, relevant external data sources such as weather data, economic indicators, and competitor information are incorporated to enrich the predictive model. These diverse datasets provide a comprehensive overview of the factors that influence product sales and pricing.

Next, a robust data preprocessing and feature engineering phase is undertaken to cleanse and transform the collected data into a suitable format for machine learning algorithms. This step involves handling missing values, handling outliers, and encoding categorical variables, among other techniques. By carefully curating the data, the model can effectively capture meaningful patterns and relationships.

The project utilizes a variety of machine learning algorithms, including but not limited to regression models, decision trees, and ensemble methods, to build and evaluate predictive models. Multiple models are trained and compared to identify the most accurate and reliable model for predicting sales. Hyperparameter tuning techniques are employed to optimize the model's performance and generalizability.

The final phase involves model evaluation and deployment. The selected model is assessed using appropriate evaluation metrics to gauge its accuracy and robustness. It is crucial to validate the model's performance on unseen data to ensure its effectiveness in real-world scenarios. Once the model has proven its reliability, it is deployed into production, enabling Rossmann to utilize the predictions for pricing optimization and strategic decision-making.

The Rossmann Retail Price Prediction project aims to leverage machine learning techniques to enhance Rossmann's competitive advantage by providing accurate sales predictions. By leveraging historical sales data and external factors, the project empowers Rossmann to make informed pricing decisions, optimize its marketing strategies, and maximize revenue. This project showcases the power of data-driven insights in the retail industry and highlights the potential for future growth and success through advanced predictive analytics.

# Table of Contents
Import Packages

Data Preparation

2.1 Load Dataset

2.2 Dealing With Missing Values

2.2.1 Count missing values in each dataset

2.2.2 Remove features with high percentages of missing values

2.2.3 Replace missing values in features with low percentages of missing values

2.3 Date Extraction

2.4 Joining Tables

2.5 Drop Subsets Of Data Where Might Cause Bias

2.6 Feature Engineering

2.6.1 Create new variable "AvgSales"

2.6.2 Create new variable "AvgCustomer"

2.6.3 Transform Variable "StateHoliday"

Exploratory Data Analysis

3.1 Correlation Heatmap

3.2 Sales Distribution

3.3 Customer Distribution

3.4 Sales Over Time

3.5 Sales Over Days Of A Month

3.6 Sales Over Weeks

3.7 Sales By Store Type

3.8 Sales By Assortment

3.9 Sales vs. Number Of Customers

3.10 Sales vs. Competition Distance

3.11 Sales By Promotion

3.12 Pair Plot

Store Sales Prediction (Regression Models)

4.1 Linear Regression (OLS)

4.2 Decision Tree Regression


