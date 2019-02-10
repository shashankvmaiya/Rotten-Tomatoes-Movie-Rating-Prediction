# Sentiment-Analysis-Movie-Review-Classification

Using data obtained from Rotten Tomatoes, we build models to classify the movie as a "fresh" or "rotten," i.e. good or bad.
<img width=400 height=200 src="./Images/rotten_fresh.png"/>

We use a bag of words representation and build vector models using CountVectorizer. Using Naive Bayes and n-gram models, prediction accuracy of 71% is achieved. Few of the top features obtained using this model include words like `intelligent, masterpiece, performance, touching` for a fresh review and words like `unfortunately, bland, unfunny` for a rotten review. Some n-gram features (n>1) for fresh review: `one of, may not, as well as, of the most` and for rotten reviews: `and not, there isnt, in the end, that the movie`. We see that for n>1, the feature set doesn't seem be as strong as the ones for n=1. 

Other models tried out include
* Random Forest Classifier
* word2vec
