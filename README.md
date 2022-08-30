# Meme_Sentiment_Analysis

Code as a part of Research Topic - 
##  Sentiment Extraction from Images using Latent Textual Features and Joint Embeddings Approach

This research study proposes a two-phase deep feature engineering framework for efficient learning of visual semantics. The underlying idea of using joint embedding with hidden textual features of text associated with a meme image and image captioning is assessed on the Memotion dataset. This ideates to identifying key terms using deep NLP models from the BERT family, Text Rank, or TF-IDF. 

Ranking scores for key terms are produced and then Word2Vec is used to generate the vector representation for each key term Wide ResNet50 and Sentence2Vec is also leveraged to extract and encode the meme category and captions embeddings. Finally, the tasks to classify sentiment and emotion type are executed with a simple ANN setup. The findings are compared with state-of-the-art results and reported.

Many tasks such as image annotation & search, zero shot learning, image caption generation, visual question answering or text classification have been recently possible largely due to ability of embedding representations of image and text in a joint space also known as joint embedding space. Image classification and text classification are most fundamental tasks in machine learning. But more recently adopted forms of communication and expression include multimodal forms such as Memes or screenshots. 

![Classification_Workflow](https://user-images.githubusercontent.com/5952578/187350484-fc4c1284-23d8-45c7-a7f1-7bf9a541fb10.PNG)

Many advancements in Computer vision and NLP area have let to development of advanced pre-trained models capable of doing image & textual sentiment classification part with ease. However, in the open online communities with memes as the new form of expression, there may be users trying to exploit the inefficiencies in the system that may not be capable of flagging a meme content based on sentiment and emotions and thus may lead to hateful attacks to a particular individual or groups. The growing adoption of memes on social media platforms such as Facebook, Instagram, and Twitter implies that such multimodal content cannot be ignored now.

To do a sentiment classification task on a multimodal content form such as memes, joint embedding approach has been tried and tested. However, the unrelated nature of meme image and allied textual content makes it a challenging task to view only through the method of joint embeddings. In this research study, to capture relation between the image text and image of a meme a new approach is proposed to include hidden textual and image features in conjunction with joint embedding to solve the task of Visual sentiment analysis.


