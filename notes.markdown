## KNN

a non-parametric supervised learning


## SVM

Find a hyperplanes that might represents the largest separation, which means the distance from it to the nearest data point on each side is maximized. 

## Word2Doc

Give each word from the bag of words an initial random vector with dimesion n. Opitimize the prediction of words by the similarity of close words.


### Continuous Bag of Words:
<br>
Use each center word's surrounding m words (+-m distance) to predict the center word by finding which word in the BOW has the biggest similarity to the set of surrounding m words. Loss is calculated by cross entropy of the softmax of probalility of all words and the one hot encoding of the center word.

### Skip-gram:



### Questions

1. Why negative sampling in Word2Vec?
2. 
