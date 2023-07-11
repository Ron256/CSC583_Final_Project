# CSC583_Final_Project
NLP Default Final Project

Using pretrained transformer models, BERT-based model in HuggingFace Models, implemented deep-learning based classifiers to detect fake news on diseases such as COVID-19, then applied Explainable AI techniques to interpret the predictions made by the model. 

The used data set consisted of 7,000 new articles, headlines and tweets. Each instance was annotated with one of the various categories (true, false, misleading, mostly false, partly false etc.)
For the input text, i used the context_text feature and the for the target category, I used the class feature. For entries where either feature was empty were ignored.

To keep things simple, entries whose class labels contained 'true' as TRUE, entries whose class labels contained 'false' as FALSE, and all other entries as UNKNOWN. 
