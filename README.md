Steps in Multinomial Naive Bayes
``` 
 P(c)=Total number of documents/Nmber of documents in class c
​
P(w∣c)=Total word count in class c+V/Count of word w in class c+1
​
+1: Laplace smoothing to handle words not seen in the training data.
V: Vocabulary size.
 ```
