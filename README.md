# Digit_Recognizer
**Dataset**:<br/>
I will be applying a variety of machine learning methods to classify handwritten digits that are part of the MNIST dataset. 

<img src="/images/digits.png" width="300" height="200" />
 
The MNIST dataset consists of a test set of 10,000 examples and a training set of 60,000 examples. This particular dataset is classified, so we will be using the supervised learning algorithms detailed below. 

**Machine Learning Algorithms**:<br/>
*K-nearest neighbor (KNN)*: The KNN method is useful for both classification and regression. An example is assigned a label based on the class of it’s k-nearest neighbors. Choosing a suitable value for k is important when implementing this algorithm. 

*Support vector machines*: SVMs are non-probabilistic binary classifiers. The SVM training algorithm assigns new samples based on given labels like we have the MNIST dataset. This is an effective algorithm for classification, regression, and outlier detection. 

*Neural networks*: Neural networks form probability-weighted associations between an input and a result. Just like KNN and SVM, it is a supervised learning algorithm. The weights of a neural network are tuned as more examples are evaluated based on the error between the processed output and a target output. 

**Evaluating Performance**:<br/>
We use two methods to validate the performance of these supervised learning algorithms. The first is using the classic train/test split provided by the dataset (i.e. train using the 60,000 samples provided and evaluate performance using the test-set). I will also use k-fold cross-validation on the training set. The algorithms will be trained using 50,000 samples and evaluated on the holdout group. We will also confirm that the training set is not biased towards certain numbers by ensuring the distribution of each of the 10 digits is approximately uniform. 

