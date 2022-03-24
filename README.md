# Spanish Suicidal Tendencies to Sentiment Analysis

This is a code to classify text into Spanish suicidal tendencies. It uses a pre-trained model to extract Word Embedding Vectors which are used later to train the model. Using pre-trained Word Embeddings is a good option at the time to create high accuracy models.

If you want to train the model using your own or another pre-train model just add it in the ``` load_word2vec() ``` function. It has to be a ``` .bin ``` file.
For example the provided by google ``` GoogleNews-vectors-negative300.bin ```. It is necessary download your pre-trained model before use it.


