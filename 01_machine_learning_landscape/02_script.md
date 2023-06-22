* Machine learning is the science and art of building systems that can learn from data. Learning defined is getting better at something with a performance measure.

* Machine learning is good for complex problems where there is no algorithmic solution. Machine learning replaces rules set by humans with systems that can adapt.

* Labeled training sets are training sets that contain the solution, i.e. a label for each instance.

* The two most popular supervised tasks are regression and classification.

* Four common unsupervised tasks include clustering, visualization, dimensionality reduction, and association rule learning.

* The reinforcement learning algorithm would perform best if you wanted to create a robot that learns to walk in many unknown terrains.

* If you do not know know how to define groups of customers you can use a clustering algorithm to segment them into clusters of similar customers, i.e. unsupervised learning.

* If you know what groups you want customers segmented into then you can feed examples from each group into a classification algorithm to classify all customers into the groups, i.e. supervised learning.

* Spam detection is a supervised learning problem. The algorithm is given many emails along with their label, i.e. spam or not spam.

* Online learning systems can learn incrementally. Batch learning systems can not. This means online learning systems can adapt quickly to changing data and autonomous systems.

* The out-of-core algorithm can handle big datasets which can not fit in the memory of a computer. It does this by chopping data into small batches and using online learning techniques to learn from them.

* Instance-based learning systems learn the training data by heart. When given a new instance they use a similarity measure to find the most similar learned instances and use them to make predictions.

* Models have one or more parameters determining what it will predict given a new instance. Learning algorithms try to find optimal values for these parameters so the model generalizes new instances well.

* Hyperparameters are parameters of the learning algorithm and not the model. The amount of regularization to apply is an example of a hyperparameter.

* Model-based learning algorithms search for optimal values for the model parameters so that the model will generalize new instances well.

* Model-based learning algorithms are trained by minimizing cost functions measuring how bad it is at making predictions on the training data. There is a penalty for complexity if the model is regularized.

* To make predictions with model-based learning algorithms you feed the features of the new instance into the prediction function of the model. You use the parameter values found by the learning algorithm.

* Six challenges in ml are lack of data, poor data quality, nonrepresentative data, uninformative features, simple models that underfit the training data, and complex models that overfit the data.

* A model is likely overfitting the training data if it performs well on the training data but generalizes poorly to new instances. To fix this you can get more data, simplify the model, or reduce data noise.

* Test sets are used to estimate the generalization error that a model will make on new instances before the model is launched in production.

* Validation sets are used to compare models. They make it possible to select the best model and tune the hyperparameters.

* Train-dev sets are used when there is a risk of mismatch between training data and data used in validation and test datasets. Datasets should be as close as possible to that used when in production.

* Train-dev sets are part of the training set that is held out, i.e. the model is not trained on it. The model is trained on all other data and evaluated on both the train-dev and validation sets.

* A model is likely overfitting if it performs well on training sets but not on train-dev sets.

* If a model performs well on both the training set and the train-dev set but not on the validation set then there is likely a data mismatch between the training data and the validation plus test data.

* Tuning hyperparameters using a test set risks overfitting it. The generalization error you will measure will likely be optimistic thus launching a model that performs worse than you expect.