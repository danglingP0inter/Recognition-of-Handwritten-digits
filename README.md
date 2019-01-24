# Recognition-of-Handwritten-digits-using-Neural-nets

An excellent tutorial to understand how the neural network works in general can be found here
https://www.youtube.com/watch?v=aircAruvnKk&t=103s

This program is a result from the motivation I got from this series of tutorial    
https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi

The problem of classifying digits can also be solved using ML classifiers (using scikit-learn package).        
https://www.youtube.com/watch?v=aZsZrkIgan0

I've used 3 different Supervised Machine learning Classification algorithms. It's not possible to say which one is the best to classify this MNIST dataset because that depends on the many criteria and they can be fine-tuned to improve their performance (which I didn't here).

The K-nearest neighbors algorithm is fast to train the data but is slow to compute the results. On the other hand, the Random Forest is faster to classify the data. The results obtained with LinearSVC were less good, but this could probably be improved by using better parameters.


Accuracy results:

Linear Support Vector Classifier(SVC): 88.9%
Random forest: 95.9%
k Nearest Neighbors(k=5): 96.2%
