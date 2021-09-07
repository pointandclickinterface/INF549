## Instructions for using these notebooks ##

This fold contains three notebooks, including two machine learning algorithms, decision tree and Naive Bayes and one text preprocessing notebook called text featurization. All the machine learning algorthims in these notebooks are implemented by a popular machine learning library called [scikit-learn](http://scikit-learn.org/stable/). You're welcome to explore it by yourself.

Also,we provide three classification datasets that could be applied to either of the two ML algorithms. 
* ["iris.data"](https://archive.ics.uci.edu/ml/datasets/iris) has four attributes with continuous values describing three different iris species.
* ["lenses.txt"](https://archive.ics.uci.edu/ml/datasets/lenses) contains four attributes with discrete values and three classes.
* ["SMSSpamCollection.txt"](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) includes 5572 SMS messages collected from four different research sources and they were labeled as spam or ham. 

**Note:** The links of the three datasets are just for your reference. We have made some changes to the datasets so please do not use the datasets from these links for your assignments. Instead, you should use datasets in the "Dataset" folder.

For decision tree, the algorithm used here is called CART (classification and regression tree), which can take both discrete and continuous values as the input. For illustration purpose, we suggest to use iris.txt and lenses.txt at first. When discrete string values are inputted, the notebook will print the codebook for each cateogrical variable. If you apply decision tree to the SMS dataset, the algorithm will learn a very deep decision tree which might be hard to visualize. In the notebook, if the tree grows too deep, only the first five layers will be displayed.

For Naive Bayes, we provide three different classifers, Bernoulli Naive Bayes, Gaussian Naive Bayes, and Multinomial Naive Bayes. They are based on different mathmatical fundations and might have different performance over different datasets.  Naive Bayes is based on applying Bayes’ theorem with the “naive” assumption of independence between every pair of features. It can take both discrete and continuous values as the input and have worked quite well in many real-world situations, famously document classification and spam filtering. Hence, it is recommended to apply Naive Bayes to the SMS dataseta. But please feel free to apply it to other datasets. 
