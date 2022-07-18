The task consists in creating a deep learning model to detect hate speech or offensive language in texts.

The dataset attached is composed of tweets from Twitter, manually labelled as: 0 - hate speech 1 - offensive language 2 - neither.

Each entry of the dataset has 7 features, representing: the index, the class, the number of words for each of the three categories and the text.

Due to the nature of the study, it’s important to note that this dataset contains text that can be considered racist, sexist, homophobic, or generally offensive.

Hint: keep in mind that tweets are full of noisy information(Hashtag, mentions, emoji, etc...), a good pre-processing phase could improve the performances of your models.  

The metric you will need to use to evaluate the overall results is the macro-f1, provide the evaluation of the f1-accuracy for the single classes as well.

Make sure to test the model in order to prove robustness and lack of overfitting.

Very very simple task classification. Dense NN is enough. 
Conv NN, RNNs, Transformers: they have not been tried.

