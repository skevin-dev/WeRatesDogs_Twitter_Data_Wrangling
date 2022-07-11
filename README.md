# WeRatesDogs_Twitter_Data_Wrangling


### Introduction

Real-world data rarely comes clean. Using Python and its libraries, In this project we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because ["they're good dogs Brent."](http://knowyourmeme.com/memes/theyre-good-dogs-brent) WeRateDogs has over 4 million followers and has received international media coverage.



![alt text](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd378f_dog-rates-social/dog-rates-social.jpg)

### Project Details

Your tasks in this project are as follows:

  * Data wrangling, which consists of:
    * Gathering data
    * Assessing data
    * Cleaning data
        
* Storing, analyzing, and visualizing your wrangled data
* Reporting on 1) your data wrangling efforts and 2) your data analyses and visualizations

### Gathering Data for this Project

Gather each of the three pieces of data as described below in a Jupyter Notebook titled <code><mark>wrangle_act.ipynb</mark></code>:

1. The WeRateDogs Twitter archive <code><mark>twitter_archive_enhanced.csv</mark></code>. It's instructed that this file be downloaded manually from an URL provided by Udacity.
2. The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (<code><mark>image_predictions.tsv</mark></code>) hosted on Udacity's servers and should be downloaded programmatically using the [Requests](http://docs.python-requests.org/en/master/) library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
3. Each tweet's retweet count and favorite (i.e. "like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's [Tweepy](http://www.tweepy.org/) library and store each tweet's entire set of JSON data in a file called <code><mark>tweet_json.txt</mark></code> file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.

### Assessing Data for this Project

After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document at least **eight (8) quality issues** and **two (2) tidiness issues** in your <code><mark>wrangle_act.ipynb</mark></code> Jupyter Notebook. To meet specifications, the issues that satisfy the below mentioned **Key Points** must be assessed.



### Cleaning Data for this Project

Clean each of the issues you documented while assessing. Perform this cleaning in <code><mark>wrangle_act.ipynb</mark></code> as well. The result should be a high quality and tidy master pandas DataFrame (or DataFrames, if appropriate).

### Storing, Analyzing, and Visualizing Data for this Project

Store the clean DataFrame(s) in a CSV file with the main one named <code><mark>twitter_archive_master.csv</mark></code>. If additional files exist because multiple tables are required for tidiness, name these files appropriately. Additionally, you may store the cleaned data in a SQLite database (which is to be submitted as well if you do).

Analyze and visualize your wrangled data in your <code><mark>wrangle_act.ipynb</mark></code> Jupyter Notebook. At least **three (3) insights and one (1) visualization** must be produced.

### Installation 

```
git clone https://github.com/skevin-dev/WeRatesDogs_Twitter_Data_Wrangling
cd WeRatesDogs_Twitter_Data_Wrangling
Jupyter notebook 
```

### Requirements
* Pandas
* Numpy 
* Seaborn
* Json 
* Tweepy 

### Author 

👤 **Shyaka Kevin**

- GitHub: [Shyaka Kevin](https://github.com/skevin-dev)
- LinkedIn: [Shyaka Kevin](https://www.linkedin.com/in/shyaka-kevin/)