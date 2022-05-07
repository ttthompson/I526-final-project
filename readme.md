This analysis is of 24 product variables and 6 customer variables from over 1.37 million customers provided and collected by the H&M Group, with the goal of exploring what factors contribute to the whether or not a customer will purchase a particular article of clothing. 

The provided data consists of three csv files: `articles`, `customers`, `transactions_train`. 
- `articles` describes product information of the individual articles of clothing being sold. 
- `customers` describes metadata pertaining to each of the recorded customers per each customer_id. 
- `transactions_train` records all the transaction history. 

I explore the following variables:
1. `club_member_status`: the loyalty rewards membership status
2. `fashion_news_frequency`: categorical variable of how frequent the customer receives
fashion rate (NONE, Regularly, Other). Potentially a good indicator of interest in fashion.
3. `age`: self-reported discrete variable of customer age
4. `postal_code`: An encrypted categorical variable to represent geographical postal codes.
5. `t_dat`: date of transaction
6. `price`: transformed measurement of price of article purchased
7. `product_type_no`: the code for the particular article of clothing name such as trousers, dress, etc. This corresponds to the product_type_name
8. `product_group_name`: the portion of the body the article falls on (Garment Upper body, Garment Lower body, etc.)
9. `graphical_appearance_no`: the numerical value of the distribution of the pattern of the article which corresponds to graphical_appearance_name
10. `colour_group_code`: the numerical value of the color/pattern of the article which corresponds to colour_group_name

The data can be downloaded from Kaggle in the competition showcase, upon conclusion of the deadline: https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data


ABOUT THE CODE:

`final_visuals.RMD` generates the final 3 plots for grading

`timeseries.RMD` explores various timeseries executed before selecting final 1

`price_plots.RMD` explores various plot combinations for the price visual before selecting final 1

`age_price_plots.RMD` explore the various plot combinations of the age and price scatterplot before selecting final 1

`data_exploration.RMD` was the initial exploration of the variables and data, including any general data engineering.




