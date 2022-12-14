# Meme_Sentiment_Analysis

Code as a part of Research Topic - 
##  Sentiment Extraction from Images using Latent Textual Features and Joint Embeddings Approach

This research study proposes a two-phase deep feature engineering framework for efficient learning of visual semantics. The underlying idea of using joint embedding with hidden textual features of text associated with a meme image and image captions is assessed on the Memotion dataset. This ideates to identifying the text sentiment using deep NLP models from the RoBERTa family and using it as latent features.

Wide GPT-2 and Sentence2Vec is also leveraged to extract and encode the meme caption and generate captions embeddings. Finally, the tasks to classify sentiment and emotion type are executed with a simple DNN setup with two dense and a regularisation layer. The results and findings from the model trained and tested are compared with state-of-the-art results and reported. The Comparison between SOTA F1-Score and F1-Score of the models produced by each experiment yielding training and testing F1-Scores was done. 

It was observed that the training F1-Score for Experiment 1,2 and 3 yields 58%, 60% and 61% better results than the SOTA F1-Scores respectively. **For the testing F1-Score, it was observed that the F1-Score for Experiment 1,2 and 3 yields 19%, 32% and 33% better results than SOTA F1-Scores respectively.**

![Classification_Workflow](https://user-images.githubusercontent.com/5952578/187350484-fc4c1284-23d8-45c7-a7f1-7bf9a541fb10.PNG)

The results from this exercise made it evident that using joint embeddings on meme type content proved to be useful in generating feature vectors that affected the final model accuracy in  a positive way since the results generated by them yielded better F1-Scores than SOTA F1-Scores. **The proposed research methodology proved to be better than the existing approach of classifying meme sentiment as per the comparison in F1-Scores. **

Through the comparison of results from the experiments of this exercise with the SOTA F1-Scores, it was observed that the models from each of the three experiments outperformed the SOTA method on the testing data. It was at least nineteen percent better when the testing data was used from a different data source. If testing data split was taken from the same data source, then the results were at least thirty two percent better than SOTA F1-Scores.

