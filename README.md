# language_detection

## Detect 21 languages of the European Parliament Proceedings Parallel Corpus 1996-2011

 Download raw data : http://www.statmt.org/europarl/
 
 Test on this data : http://www.statmt.org/europarl/

The main considerations in this task are:

1.How to avoid loading the 1,5 GB into memory. 

2.Designing sets with balanced classes. 

3.Using classical Natural Language Processing methods that allow you to get fast,cheap and very good results. 

First, check how the train, validation and test sets where built and preprocessed [here](https://github.com/Salma-Bouzid/language_detection/blob/master/Build_dataset.ipynb) 

Second, check how we trained our Logistic regression model without running into memory erros on a Macbook pro [here](https://github.com/Salma-Bouzid/language_detection/blob/master/Train.ipynb)

