# Bitcoin-Sentimental-Analysis
## Bitcoin Sentimental Analysis through tweets

Cryptocurrencies such as Bitcoin (BTC) attracted a lot of attention in recent months due to their unprecedented price fluctuations. This paper aims to propose a new method for predicting the direction of BTC price with sentiment analysis algorithm.

## INTRODUCTION
 
In any financial market sentiment gets its own place and is used as a strong indicator to predict whether the market will outperform or not. As crypto-currencies are emerging passively in the financial markets, our goal is to determine what sentiment individuals and organizations have. As bitcoin leads the market so our research will be based on it to predict the sentimental analysis for the overall market. It has three major footsteps to follow. Firstly, to accumulate data from twitter by using twitter developer Api , secondly we have to clean the data first in order to achieve the relevant data. Lastly and the most significant thing of the model is applying the sentimental algorithm which will compare the threshold of sentiments among our data.

In this study, we examine Twitter, a popular microblog, and develop models for categorising "tweets" into positive, negative, and neutral emotion. We create models for categorising sentiment into positive and negative categories, as well as a three-way task that categorises sentiment into positive, negative, and neutral categories. On the test data, including news sentiment resulted in the maximum forecast accuracy of 0.585, which is better than a random guess. Within their respective model classifiers, the model with asset specific (news sentiment and asset specific) input features scored best, implying that both BTC news sentiment and asset specific are important elements in predicting tomorrow's price direction.

Our feature-based model with only 100 features achieves the same level of accuracy as the model with over 10,000 features. We give a detailed feature analysis of the 100 features we suggest in this study. Our tests demonstrate that attributes related to Twitter-specific features (emoticons, hashtags, etc.) add little to the classifier's usefulness. For both classification tasks, features that integrate prior polarity of words with their parts-of-speech tags are particularly relevant. As a result, we can observe that typical natural language processing methods can be beneficial in genres other than the one in which they were taught (newswire).

## Project Flow:
### 1. Extracting 10,000 tweets using Twitter API:

![image](https://user-images.githubusercontent.com/102557215/183733190-000c2194-d59f-4860-ba07-f14a86ceae63.png)

### 2.	Fetched 10,000 tweets:

![image](https://user-images.githubusercontent.com/102557215/183733352-5fb5a986-f63e-4842-bd79-f6822be298ea.png)

### 3.	Cleaning the extra symbols and hashtags:

![image](https://user-images.githubusercontent.com/102557215/183733489-a3494d9b-f532-4ac5-826c-bb4a873ac33d.png)

![image](https://user-images.githubusercontent.com/102557215/183733654-7c93f137-f38f-45c3-b782-da1e2e419d3a.png)

### 4.	Measuring subjectivity, polarity and sentiment of tweets:

![image](https://user-images.githubusercontent.com/102557215/183733825-0b5f97c1-e42f-4e3c-aeb1-5d761249ba6a.png)

## Output:

### 5.	Scatter plot of sentiments of the 10,000 tweets:

![image](https://user-images.githubusercontent.com/102557215/183734014-dcd5b2d5-23f9-48de-99d8-8ad90dfe2ac9.png)

### 6.	Pie chart to present the biased on BTC:

![image](https://user-images.githubusercontent.com/102557215/183734190-56d553fa-0e75-49c3-8920-c33ee09649aa.png)

## For tweets you have to apply at:
[Twitter Developers Api](https://developer.twitter.com/en/portal/petition/essential/basic-info)







