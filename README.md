# Sentiment_analysis_for_movie_reviews_tamillanguage


# Project overview

  Our objective is to detect whether the movie will succeed or not based the reviews on YouTube given by the people who watched the movie. In precise we work on the movie reviews which are written in direct Tamil [தமிழ்] language. We proceeded with algorithm based and lexicon-based methods for calculating the sentiment of the movie reviews. The concept is to create a corpus from the scraped YouTube reviews and translating them into English. Then to do sentiment scoring by various approaches to do sentiment classification. Finally, to predict the success of the movie.
  
# Methodology

![image](https://user-images.githubusercontent.com/94525493/217303455-b942c5ca-275f-4ff2-b2ff-186d458548b0.png)

# Conclusion
  Five heuristic approaches have been applied to score the sentiment values. i.e) word frequency, afinn, textblob, vader sentiment and manual scoring. Among those five approaches manual scoring performs well with 63.125% accuracy whereas textblob has poor performance with lowest score of 56.456%. We presented a proposal for classifying the Tamil movie reviews using supervised algorithms, namely SVM, Random Forest, Logistic regression and Multinomial Naive Bayes. Features are extracted and are given to the system for better classification and to improve the accuracy of the system. The accuracy of different classifiers with word feature are represented in the table. The Random Forest [RF] classifies better than other classifiers with more accuracy.
  
# Result 

![image](https://user-images.githubusercontent.com/94525493/217304378-cfbbb766-1e62-4f46-8fc4-81231aed1e58.png)

Test a model for particular movie Reviews @ Sarpatta Parambarai movie

![image](https://user-images.githubusercontent.com/94525493/217304761-252aa7f6-398b-4aef-93db-21448b0ce55c.png)

  
# Feature Enhancement

	For future work, fine grained tagging can be done where, these reviews can be fine grained into very positive, positive, very negative, negative and neutral.
	Unsupervised way of implementing data can also be done as forthcoming work.
	More than trigram approach can be used to improve the positive and negative word corpus.
	Tokenized words may further stem or lemmatized to get precise corpus.

