# Sentiment_Analysis_Covid19_Vaccinations_Tweets

**Introduction**

The global health crisis brought on by the Covid-19 pandemic has resulted in an unceasing stream of covid cases. On social media, millions of people expressed their views on vaccination in addition to the numerous organizations. In this regard, our study uses Twitter dataset to analyze the various perspectives of people about the Covid-19 vaccination. The word embedding method is being used in this effort to analyze the sentiment of the Covid-19 vaccination. The phrase "word embedding" refers to the representation of words for text analysis, often in the form of a real-valued vector that encodes the meaning of the word in order to predict comparable meanings for words that are adjacent to one another in the vector space. The sentiment analysis of the text that is included in the Twitter dataset is described in this notebook. Various NLP tools, including Nltk, Sklearn, Textblob, etc., as well as the Python libraries NumPy, Pandas, and Matplotlib, will be used. The project is split into two sections. In the first section, we analyze the Twitter dataset by carrying out a number of operations such eliminating stop words, punctuation, stemming, and doing sentiment analysis on the text that contains. The following stage entails vectorization using TF-IDF. SVM, RandomForests, and KNN approaches are used to train the model. Finally, we will be assessing the model performance using unseen test data.

**Dataset Description**

The dataset is obtained from the tweets of covid-19 vaccination from 2019 year. The dataset has numerous columns including tweets. The main column we are considering here is the "text" which contains all the tweets. 

**Results**

There was a rapid rate of COVID-19 vaccination for the entire population. This research suggests analyzing the various viewpoints on the COVID-19 immunization across the global Twitter dataset. Prior to performing any text analysis, it is important to clean up the data by removing stop words, punctuation, and links from text columns. Before beginning the analysis, we need to remove the null values if any. This facilitates our analysis of the crucial portions of the data. The project uses two methods. 

* First, it creates various sentiments—positive, negative, and neutral—based on the various vaccine types that are mentioned in the text. Based on the analysis the majority of the tweets in the dataset belong to neutral and positive sentiments. For the aforementioned initial phase, we employed a variety of Python modules, including Nltk, Textblob, NumPy, Pandas, and TensorFlow. WordCloud is used to graphically represent the common words in a corpus and for each sentiment.  
* Secondly, machine learning and deep learning techniques are further used for sentiment analysis and training the model. Word2Vector is used to create a vector space to display trained tweets.

In addition, SVM (Support Vector Machine), RandomForests, and KNN are used to classify sentiment. According to the results, Random Forest and KNN outperform SVM with an accuracy of 60% and 63.33%, respectively, demonstrating the model's strong performance. Further, SVM produced accuracy of 58.33%, which is nearly equal to that of the other two models. This research demonstrates that, in comparison to the other two attitudes, the ratio of negative sentiments declined.


