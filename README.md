# YesBank closing stock  price prediction
# OBJECTIVE
The "Yes Bank Closing stock Price Prediction " project is a supervised machine learning regression capstone project designed to develop a predictive model that forecasts the closing prices of Yes Bank, one of the leading banks in India. This project leverages historical data, machine learning techniques, and regression algorithms to provide valuable insights and predictions for investors, traders, and financial analysts.
Background: Financial markets are characterized by their volatility and complexity. Predicting stock prices is a challenging task, and accurate forecasts can provide a competitive advantage in making investment decisions. In this project, we aim to utilize supervised machine learning techniques to build a robust model that can forecast Yes Bank's closing prices with reasonable accuracy.
Project Objectives: The primary objectives of this capstone project are as follows:
Data Preprocessing: Clean, preprocess, and transform the raw data into a format suitable for machine learning. This step includes handling missing values, feature selection, and scaling.
Model Selection: Explore and select appropriate regression algorithms for the task. Experiment with different models such as Linear Regression etc to find the best-performing one.
Feature Engineering: Engineer relevant features that can enhance the predictive power of the model.
Model Training and Evaluation: Split the dataset into training and testing sets to train the chosen regression model. Evaluate the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
Hyperparameter Tuning: Fine-tune the model's hyperparameters to optimize its predictive accuracy.
Benefits: The successful completion of this capstone project will offer several benefits:
Investment Decision Support: Investors and traders can use the model's predictions to make informed decisions about buying, selling, or holding Yes Bank's stock.
Risk Management: Financial analysts can use the forecasts to assess and manage risks associated with Yes Bank's stock.
Educational Resource: This project can serve as an educational resource for individuals looking to learn about machine learning, data analysis, and stock price prediction.
Future Enhancements: The project can be expanded to include more advanced machine learning techniques, real-time data integration, and additional features for a more comprehensive stock analysis tool.
By leveraging supervised machine learning regression techniques, the "Predicting Yes Bank Closing Prices" capstone project aims to provide a valuable tool for stakeholders interested in Yes Bank's stock performance, ultimately aiding in making more informed financial decisions.

# Problem Statement
In this Supervised Machine Learning Regression Capstone Project, our primary objective is to develop a predictive model that accurately forecasts the closing stock prices of Yes Bank. Yes Bank is a prominent Indian financial institution, and its stock prices are subject to various economic, financial, and market factors. Accurate predictions of these prices can provide valuable insights for investors, traders, and financial analysts

# Attribute Information

Date: Monthly observation of stock since it listed.<br>
Open: The price a stock when the stock exchange open for the day.<br>
High: The maximum price of a stock attain during given period of time.<br>
Low: The minimum price of a stock attain during given period of time.<br>
Close: The price of a stock when the stock exchange closed for the day.<br>



# CONCLUSION
It has been seen that the stock price fall after 2018 fraud case.
Data comprises of 5 variables only.
Added three more variables. One is month number as it plays a crucial role as there is financial result announcements. Another is Year and pivot,
We found no null values in the data.
Data is positively skewed so log transformation is applied.
There is no outliers observed so the data is clean.
There is no categorical column so no need for dummies.
Then we model the data with 4 types of regressions.
As per the above data Elastic net regression is quiet better in all the metrics. So we will select this model for upcoming predictions.
Also it has been found out that R2 value is more correlated with pivot.
By seeing the model accuracy it can be used confidently for upcoming predictions.
