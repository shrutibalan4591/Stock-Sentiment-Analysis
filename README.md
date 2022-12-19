# **Stock-Sentiment-Analysis**

## **Objective**

This is an end-to-end ML project, which aims at developing a classification model to predict the increase or decrease in stock market prices, based on the sentiments extracted from news headlines.

The classifier used for this project is RandomForestClassifier.

Deployed in Railway.app.

Link to the application : https://stock-sentiment-analysis.up.railway.app/

************************************************************************************************************

## **Dataset Information**

Description:

Data used for this problem in this dataset:

**CombinedNewsDJIA.csv:** two columns The first column is "Date", the second is "Label", and the following ones are news headlines ranging from "Top1" to "Top25". All news are ranked from top to bottom based on how hot they are. Hence, there are 25 lines for each date. The news headlines has been obtained by crawling historical news headlines from Reddit WorldNews Channel (/r/worldnews). They are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date.(Range: 2008-06-08 to 2016-07-01)

This a binary classification task. Hence, there are only two labels:

"1" when Adj Close value rose or stayed as the same;
"0" when Adj Close value decreased.

************************************************************************************************************

## **App Interface**

![image](https://user-images.githubusercontent.com/77207245/208407409-9969a4dd-1560-497a-aa29-f3978eb26ead.png)

************************************************************************************************************

## **Directory Tree**

![image](https://user-images.githubusercontent.com/77207245/208459559-c3169477-50b2-46de-9834-0eaadfca622d.png)


************************************************************************************************************

