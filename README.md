Customer Shopping Trends Analysis
📚 Overview
This repository contains an exploratory data analysis (EDA) of customer shopping trends, including demographic analysis, shopping behaviors, geographical patterns, preferred payment methods, and shipping preferences. The data was sourced from a dataset that includes information about customers' purchases, product details, and their associated behaviors.

🔑 Key Features
Customer Demographics: Insights into the age and gender distribution of customers.
Shopping Behavior: Analysis of frequently purchased items, purchase amounts, and the relationship between review ratings and purchase frequency.
Geographical Insights: Trends in spending across different locations.
Payment Preferences: Analysis of preferred payment methods and how they vary across demographics.
Shipping Preferences: Investigation of the most popular shipping methods.
🧳 Dataset
The dataset used in this analysis contains the following key features:

Customer ID: A unique identification number for each customer.
Age: The age of the customer.
Gender: The gender of the customer (Male, Female).
Item Purchased: The name of the product purchased.
Category: The category the product belongs to (e.g., Clothing, Electronics).
Purchase Amount (USD): The total amount spent on the purchase.
Location: The geographic location of the customer.
Size: The size of the purchased item (e.g., S, M, L, XL).
Color: The color of the purchased item.
Season: The season in which the purchase occurred (e.g., Winter, Summer).
Review Rating: The rating given by the customer (1-5).
Subscription Status: Whether the customer is a subscriber.
Payment Method: The method used to pay for the purchase (e.g., Credit Card, PayPal).
Shipping Type: The type of shipping chosen (e.g., Standard, Express).
Data Cleaning and Preprocessing
Missing values were handled, and column names were cleaned for consistency.
Categorical data (e.g., Gender) was encoded numerically for analysis.
💻 Code Structure
1. Data Overview
The notebook starts with loading and displaying basic information about the dataset.
It checks for missing values and provides summary statistics.
2. Exploratory Data Analysis (EDA)
I. Demographics
Insights into the average age of customers, gender distribution, and spending habits by age group.
II. Shopping Behavior
Analysis of frequently purchased items, average purchase amounts, and the relationship between review ratings and purchase frequency.
III. Geographical Analysis
Comparison of average purchase amounts across different locations.
IV. Preferred Payment
Analysis of the most frequently used payment methods and preferences by location.
V. Preferred Shipping Method
Insight into the popularity of different shipping methods.
3. Visualizations
Visualizations are provided for each analysis section using matplotlib and seaborn to make the insights more accessible.
🚀 How to Run the Code
Clone this repository to your local machine or open the Jupyter notebook in an online environment like Google Colab.
Install the required libraries by running the following commands:
bash
pip install pandas numpy matplotlib seaborn
Run the Jupyter notebook to explore the analysis.
📈 Results
Demographics: Most customers are between 19-30 years old, with a higher proportion of male customers.
Shopping Behavior: The top items purchased are from the clothing and electronics categories, and the average purchase amount is lower for most customers.
Geographical Trends: Alaska has the highest average purchase amount, while Connecticut has the lowest.
Payment Preferences: Credit card is the most frequently used payment method.
Shipping Preferences: Free shipping is the most popular choice among customers.
