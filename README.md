# Project 3: Web APIs & NLP


I am currently a Data Analyst at Naver.com, Korea's #1 search engine. It is practically the Google of Korea. It consists of all matters of Korea from politics to entertainment shows, from movies to celebrity updates and from Kdrama to Kpop. it has always been my dream to work in the major search engine company ever since it became the search engine of Korea. 

By taking in small samples such as just Kdrama and kpop, we can test whether one test will have greater impact on finding the true subreddit or not. Through the research, I conducted logistic regression model and K Nearest Neightbors Classifier. By looking at the score, we are able to see that the model for logistic regression is pretty perfect. About 99% of the variability in y is explained by the x-variables in our model. However, when it comes to KNN, the chance of explaining the variability of y becomes slim. It reduces to 71% with train data and 55% with test. This test is overfitting and difficult use as the main model to decipher the subreddit posts. 

In suggestion to bring subreddit's interactive features into the NAVER search engine for cooperation, we would need to counter vectorize the strings and perform a logistic regression on the model. This will help to make our searches go smoother and less of error in searches.
