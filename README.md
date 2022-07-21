# wrangle-act
## by Chigozie Chukwu

# Dataset

Wrangle project analysis consist of three dataset downloaded from tweets of variety of dog types. df_archive dataset consist of 2356 entries with 17 columns. This columns included retweet id's which are not needed for this analysis. df_image consists of 2075 entries with 12 columns, consisting of various dogs that were posted and its image url's. df_tweets had 2354 entries with 3 columns; id, retweets_count and favorite_count. tweet_id were duplicated in the three datasets and df_archive had a number of missing values. This analysis started on the 13th of june 2022 and was completed on the 19th of june, 2022. it took an approximate of 7 days to complete

# Summary of Findings

Descriptive analysis was done on the three tables to get the mean, max, min, percentage, number of missing values, number of duplicates, value counts of each variables and their unique value.
The problems identified in the assessment stage were cleaned using pandas functions. we ended up having two tables; archive_new and df_image_cleaned. These two tables were used for the exploratory data analysis.
The value counts of the varierty of dog stages were gotten. The mean value of the retweeet_count and the maximum value of the retweet counts and favorite counts, together with the tweet-id associated with it.

# Key Insights

This analysis shows that pupper were posted most often (66%) , while flooper were the least that appeared on tweets posts.

![image](https://user-images.githubusercontent.com/106730045/180287407-36554d1f-95d9-4b1f-b057-ec6232b4490a.png)
