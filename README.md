# Twitter_Venezuela_Food

*!Chevere! Forecasting Tweet Location with Big Data*

__Abstract__: Social media from countries with limits to free speech is often the most reliable source of event occurrence and is a reliable alternative form of journalism. Spatiotemporal analysis of location-based social media data allows new ways to describe events. Almost 37,000 Spanish geo-tagged Tweets from the city of Caracas, Venezuela were used to observe reactions to the food shortage crisis within each of the city’s five municipalities. The number of Tweets over time is explored. The hypotheses of whether certain Tweets are particular to a municipality location is tested using multinomial naïve Bayes, logistic regression and k-nearest neighbor machine learning classifiers.

__Data__: There were 37,216 filtered Tweets from December 2014-October 2016.

__Results__: The Random forest accuracy is 0.348 with a log loss of 1.513 and a 9% improvement over the baseline. Multinomial Naïve Bayes has an higher accuracy of 0.383 and is a 20% improvement but has a worse log loss than the random forest of 2.899. Decision Tree has an even higher accuracy of 0.431 and higher percent improvement over the baseline of 35% but a worse log loss than the previous two algorithms of 6.643. k-Nearest Neighbor has an accuracy of 0.438 and 37% improvement and has a reasonably lower log loss of 2.835. Finally, the logistic regression algorithm has the highest accuracy of 0.448, a low log loss of 1.532 and a 40.4% improvement over the baseline.

