# Stat170-Project
An in-class project for the fourth-year undergraduate student in Data Science at UCI.

## Author
- Jiawen Zhang jiawez18@uci.edu            
- Kaiwen Hu kaiwenh4@uci.edu 
- Yijun Zhou yijuz13@uci.edu 

# File description
## Data collecting
- Census Bureau
    - collect_data.ipynb: Code for colllecting data from ***Census Bereau***.
    - Census_ Bureau_clean.csv: Cleaned data output by **pandas**.

- Google Place
    - google_place.ipynb: Using ***Google Place API*** to get info of shops.
    - google_place_SQL_update.sql: Add table to the local PostergreSQL database.

- Google Trend
    - Google_trend.ipynb: Using pytrend to obtain searching index of ***Google Trend***. 

- Yelp
    - Yelp_API_price_add.ipynb: Adding Price level for each shops by using ***Yelp Fusion API***. 
    - yelp_data_setup.sql: Code for create tables for ***Yelp*** data in SQL. 
    - yelp_explore.ipynb: Code for exploring the structure and data types for ***Yelp*** dataset. 
    - yelp_import.ipynb: Code for importing ***Yelp*** data into SQL dataset. 

## Feature Engineering
- word2vec
    - word2vec.ipynb: Training a new ***word2vec*** model by all the yelp reviews.
    - saved_*: Saved ***word2vec*** model.
    - Expand_W2V_to_columns.ipynb: Convert ***word2vec*** output from string to 100 attributes. 
- yelp
    - shop_distance
        - shop_distance.ipynb: Computing how many Coffee and Tea in certain distance(like shops in 100m, 50km).
        - shop_distance.sql: Adding a table storing the shop_distance information in ***SQL***.
    - expand_time_for_review.ipynb: Extra month, quarter, and year from the timestamp.
    - photo_count_and_label.ipynb: Count number of photo and labels (provided by ***Yelp***) in reviews for every shops.
    - shop_review_avg.sql: A ***SQL*** view that taking average for review attributes(like average cool) by shops.
    - shop_static_info.sql: A ***SQL*** view that contain all the static informatio of certain shop.
    - shop_user_avg.sql: A ***SQL*** view that calculate the average of user statictis in shop level. 
    - yelp_feature extraction.ipynb: Unpack json format attributes provided by Yelp, and convert those boolean value to numberic value for later modeling.
    - Yelp_reivew_vadar.ipynb: Code to get the ***Vadar*** sentiment result.
- yolo
    - yolo_v5.ipynb: Applying ***Yolo v5*** to all the review pictures.
    - yolo_group_by_shop.ipynb: Group the ***Yolo*** result by shops.
- Census_feature.ipynb: Cleaning and extraing features from the original ***Census Bureau*** data.
- dynamic_features.ipynb: Aggregating all the variables that are relative to time for Autoregressive model.

## visualization
- Photo_Caption.ipynb: Creating word Cloud for photo captions in Yelp reviews.
- rating_distribution.ipynb: Plot the weighted rating(target variable) distribution.
- review_count_vs_trend.ipynb: Plotting the time-series plot of cumulative Yelp review count and trend of searching index. 
- wordcloud.ipynb: Creating word Cloud for Yelp reviews.

## modeling
- autoregressive.ipynb: Code for our Autoregressive Model.
- linear_regressive.ipynb: Code for multiple linear regressive and Penalized regression models.

## **demo.ipynb**: Our demo notebook for our project.

## .gitignore
It helps us to ignore the change notice for the sources files in the local document. 

