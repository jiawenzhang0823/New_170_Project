# Stat170-Project
An in-class project for the fourth-year undergraduate student in Data Science at UCI.

## Author
- Jiawen Zhang jiawez18@uci.edu            
- Kaiwen Hu kaiwenh4@uci.edu 
- Yijun Zhou yijuz13@uci.edu 

# File description
## Data collecting
- Census Bureau
    - collect_data.ipynb: Code for colllecting data from Census Bereau.
    - Census_ Bureau_clean.csv: Cleaned data output by *pandas*.

- Google Place
    - google_place.ipynb: Using Google Place API to get info of shops.
    - google_place_SQL_update.sql: Add table to the local PostergreSQL database.

- Google Trend
    - Google_trend.ipynb: Using pytrend to obtain searching index of google trend. 

- Yelp
    - Yelp_API_price_add.ipynb: Adding Price level for each shops by using Yelp Fusion API. 
    - yelp_data_setup.sql: Code for create tables for yelp data in SQL. 
    - yelp_explore.ipynb: Code for exploring the structure and data types for yelp dataset. 
    - yelp_import.ipynb: Code for importing yelp data into SQL dataset. 

## Feature Engineering
- word2vec
    - word2vec.ipynb: Training a new word2vec model by all the yelp reviews.
    - saved_*: Saved word2vec model.
    - Expand_W2V_to_columns.ipynb: Convert word2vec output from string to 100 attributes. 
- yelp
    - shop_distance
        - shop_distance.ipynb: Computing how many Coffee and Tea in certain distance(like shops in 100m, 50km).
        - shop_distance.sql: Adding a table storing the shop_distance information in SQL.
    - expand_time_for_review.ipynb: Extra month, quarter, and year from the timestamp.
    - photo_count_and_label.ipynb: Count number of photo and labels (provided by Yelp) in reviews for every shops.
    - shop_review_avg.sql: A SQL view that taking average for review attributes(like average cool) by shops.
    - shop_static_info.sql: A SQL view that contain all the static informatio of certain shop.
    - shop_user_avg.sql: A SQL view that calculate the average of user statictis in shop level. 
    - yelp_feature extraction.ipynb: Unpack json format attributes provided by Yelp, and convert those boolean value to numberic value for later modeling.
    - Yelp_reivew_vadar


## .gitignore
It helps me to ignore the change notice for the sources files in the local document. 

