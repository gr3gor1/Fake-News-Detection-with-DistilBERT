# Fake-News-Detection-with-DistilBERT
Thesis Project

This repository contains the code developed as part of my thesis to fulfill the requirements for my studies at the School of Electrical and Computer Engineering, NTUA. The main goal of the project is to effectively detect fake news in text samples from articles, news, interviews, speeches, and social media. The approach applied aimed to explore the possibility of using a transformer-based model as an encoder and to compare it with traditional encoding methods (Word2Vec, TF-IDF, GloVe). Additionally, DistilBERT was chosen as an encoder to examine the method's applicability in resource-limited environments such as Google Colab. The datasets separately used include PHEME, ISOT, FakeNewsChallenge, FakeNewsNet, and LIAR. The steps that were taken in order to reach our goal are the following:

1. Preprocess the dataset.
2. Utilize the DistilBERT tokenizer for text classification from the transformers library.
3. Employ DistilBERT for text classification using the transformers library and train it on the provided data.
4. Evaluate the samples and extract the embeddings.
5. Input the data into various neural networks developed as part of the project, followed by a straightforward testing process to assess the effectiveness of each model.
6. Conduct a cross-validation process to better gauge each model's generalization ability.

