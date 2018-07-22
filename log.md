# 100 Days of Machine Learning Code - LOG
## Day 1: 16 July 2018 

**Today's Progress** : Implemented a linear regression model to predict housing prices with scikit and learnt about fine-tuning it via grid search, randomized search and ensemble methods. Followed tutorials from the textbook: Hands on Machine learning and used various medium articles to supplement theories that was hard to understand

**Thoughts**: It was great to apply linear regression a concept that I had learnt in previous math classes to machine learning and come up with a real-life solution to a problem. I was surprised by how simple it was to actually implement the model and learnt that a challenging aspect was rather in cleaning, normalizing and scaling the dataset. 

**Link of work**: https://github.com/tanster1234/100daysofML/blob/master/Work/Housing.ipynb

## Day 2: 17 July 2018 

**Today's Progress**: Learned to train a binary classifier using stochastic gradient descent(SGD) from sci-kit Learn's SGDClassifier Class for the MNIST dataset. Then used various performance measures such as precision and recall graphs and a ROC curve to see how precise the classifier is and how well it can recall. After learning binary classification went onwards to multi-label classification, using K nearest-neighbor algorithm. Managed to classify the dataset at 97% accuracy by using gride search for KNeighborsClassifier. 

**Thoughts**: Implementing SGD and KNearestNeighbors was pretty easy with very little lines of code needed, what was much harder though was how to measure the performance of the classifier using cross-validation and precision/recall. Learning about the precision/recall tradeof was pretty enlightening and I quite enjoyed it. 

**Link of work**: https://github.com/tanster1234/100daysofML/blob/master/Work/Classification%20(MNIST).ipynb

## Day 3: 18 July 2018

**Today's Progress**: Learned more deeply about linear regression and how to find optimal parameters using the normal equation and by using various gradient descent methods such as batch gradient descent and stochastic gradient descent. Then went on to learn about polynomial regression and looked at new types of Regularized linear models such as Ridge regression, Lasso regression and elastic net. 

**Thoughts**: This was quite math heavy as it required a deeper understanding of how the statistical princples and equations relate, didn't work on a dataset for today but rather just experimented with various methods of finding the best model. 

**Link of work**: https://github.com/tanster1234/100daysofML/blob/master/Work/Training%20Linear%20Models.ipynb

## Day 4: 19 July 2018

**Today's Progress**: Read up on logistic regression but rather than trying to implement, learned about the mathematical theory behind it and read onwards about softmax regression.

**Thoughts**: While I think I'm getting a solid understanding of various types of regression, I still need to understand which cases require what kinds of regression algorithms. I feel that to get a better grasp of which regression algorithm to use over one another may require further depth in the mathematics behind them. Will either read up more on that or move on in trying to implment these for various kinds of datasets.

## Day 5: 20 July 2018

**Today's Progress**: Learned about support vector machines and implemented them on the moon's dataset in sci-kit learn's library. This was non-linear SVM classification and so used polynonmial kernel and Gaussian RBF Kernel to try and find the most optimal model. Grid search is one of the easiest ways to fine-tune the hyperparameters for the most optimal model. 

**Thoughts**: I had heard about SVM before starting this however didn't know how to implement them. Now that I do I am glad I can add this tool to my toolkit in analyzing various kinds of datasets. Although which kind of SVM model to use and when is still a question. 

**Link of work**: https://github.com/tanster1234/100daysofML/blob/master/Work/Support%20Vector%20Machines%20Examples.ipynb

## Day 6 : 21 July 2018

**Today's Progress**: Learned more deeply about how the SGD classifier and regressor works in the context of the MNIST dataset, also read up briefly on the basics of neural networks. 

**Thoughts**: During my research into SGD explanations were either sometimes too mathematical or too basic, today I asked a ML expert to explain it to me clearly and I finally understood exactly what the concept of SGD is. He said that while SGD may be powerful it is not what is used in industry according to him. He suggested to read up on the Adam algorithm in the PyTorch library which uses an adaptive learning rate and many more features to make it a far more accurate algorithm to use than SGD.

## Day 7: 22 July 2018

**Today's Progress**: Read up on Decision trees, how they work, the math behind them, the entropy involved and the advantages and disadvantages of implementing decision trees. 

**Thoughts**: This wasn't very difficult to understand as I had come up on similar kinds of trees in programming algorithms, binary search trees for example. I had already implemented decision trees in Day 1 when I was working with the housing dataset, and now I have a clearer understanding of how they work. 
