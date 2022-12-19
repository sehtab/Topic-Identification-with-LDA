# Topic-Modeling-with-LDA



https://colab.research.google.com/drive/1fV7oAIExiEBoSkHePVEAqwrO4YepIWw2?usp=sharing 


# Objective:

The objective of this ICP is to identify topic from several sources. One of the source is Reddit. With Reddit API text sources are scraped and dataframe is created. 
With some data cleaning and tokenization Latent Dirichlet Analysis (LDA) is done. 

# Approaches

At first, necessary libraries are imported. The dataset is uploaded then tokenized and splitted. After tokenization LDA is applied to get the topics. 
In this way, topics are collected from sources.

At first twitter comments in the form of CSV are combined to make a single csv file and tokenized and analyzed with LDA. 
Then Reddit API is used for Reddit comments scraping and after that dataframe is created from three dataframe from Reddit commnets with three topics.
After tokenization, with LDA analysis topics are extracted from the dataframe.

# Datasets

For this ICP from dataset from kaggle are used. Twitter comments in csv format are used for LDA analysis. 
At last, user comments are scrapped from Reddit by Reddit API and analyzed.

# Results:

Results are generated with sklearn library with LDA and tf-idf.

# Challenges

For this icp, it takes a lot of time to scrap data from Reddit API for mistakes in credentials.

# Planned Work

praw library is installed and attched with this notebook and from Reddit API users' comments from different topics are scrapped in txt format 
and then dataframes are created and combined to one dataframe and with some cleaning ang tokenization, LDA analysis is done and topics are collected from the dataframe.

![image](https://user-images.githubusercontent.com/70243598/193722198-359020cd-ecbb-4c2a-af92-5572b5a4601c.png)
![image](https://user-images.githubusercontent.com/70243598/193722280-6e4c292c-8558-4f58-a1f2-efb775653b92.png)
![image](https://user-images.githubusercontent.com/70243598/193722325-5df4b279-f627-42d0-8341-a90aa03db420.png)
![image](https://user-images.githubusercontent.com/70243598/194224105-62619b07-0601-4895-b339-031aaa2ea00a.png)


With increasing n_compenents, a hyperparameter for LDA, LDA can dive deep into the topics.
