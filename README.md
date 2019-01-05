# Data Wrangling -  Data Analyst Nanodegree with Udacity
This poject was completed as part of Udacity Data Analyst Nano Degree course requirements.
<br>
# Datasets
* twitter-archive-enhanced.csv : Contains basic tweet data provided by WeRatedogs Twitter page. 
<br>
* image_predictions.tsv: Contains predictions of the dog's breed in each tweet according to nueral network.
<br>
* fav_ret_count.csv: Contains the favourite and retweet counts of each tweet. The data is available in twitter's API. By using IDs in     twitter-archive-enhanced.csv, I queried Twitter's API to obtain each tweet's JSON data using the Tweepy library and stored the data in   the text file named tweet_json.txt
<br>
* twitter-archive-enhanced.csv: I queried API to obtain tweet's JSON data using the Tweepy library and stored the data in text file       names as <br>
* tweet_json.txt. Then, I read the text file to obtain each tweet's favourite and retweet counts and saved it into this csv file.
<br>
* twitter_archive_master.csv: The clean dataset that was created by combining and cleaning the above three datasets. This dataset is not   completely cleaned as doing so will require substantial time, but it is sufficiently cleaned for the purpose of this analysis.
<br>
* query_errors.csv: This file was generated when querying Twitter's API to record the IDs of tweets which the API queries were             unsuccessful. Not used in the analysis.
# Other files:
<br>
* wrangle_act.ipynb: Jupyter notebook that contains details and codes for the data wrangling and analysis process.
<br>
* wrangle_report.pdf: A report that summarizes the wrangling process.
<br>
* act_report.pdf: A report that summarizes the findings of the analysis.

# Future Scope
As mentioned in the Datasets section, the dataset was not completely cleaned. Therefore, future work will involve further cleaning of the dataset. In addition, I will also conduct more analysis on the dataset.

# Libraries Used in the Project
* numpy 1.13.3
<br>
* pandas 0.22.0
<br>
* matplotlib 2.1.0
<br>
* seaborn 0.8.0
<br>
* requests 2.18.4
<br>
*tweepy 3.5.0
