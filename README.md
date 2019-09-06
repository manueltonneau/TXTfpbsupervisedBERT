[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **TXTfpbsupervisedBERT** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of QuantLet : TXTfpbsupervisedBERT

Published in : TXT

Description : Sentiment classification using BERT (Devlin et al, 2018). 
The results are evaluated using Malo et al. (2014)’s « Sentences_66Agree.txt ».  
We compare BERT's performance for sentence classification with the lexicon method, 
using Loughran and MacDonald (2011)'s dictionary and with Support Vector Machine (SVM) 
with TF-IDF, Word2Vec and Doc2Vec embeddings. 

The code to draw results from the lexicon method can be found here:
https://github.com/QuantLet/TXT/tree/master/TXTfpblexical

This training set is available at:
https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10

The code for SVM parameter tuning can be found here:
https://github.com/QuantLet/TXT/tree/master/TXTfpbsupervised

The tutorial used for training BERT can be found here: 
https://medium.com/@abhikjha/fastai-integration-with-bert-a0a66b1cecbe 

The adaptation of the code to our case for training BERT can be found here: 
https://colab.research.google.com/drive/11zeT5R3mGAiaQ9Vu5J7ujoFGOMbky6qV 


Keywords : text mining, sentiment, classification, transfer learning, BERT, support vector machine

See also : TXTfpbsupervised for SVM baseline

Author : Manuel Tonneau

Submitted : Thu, Sep 13 2019 by Manuel Tonneau
