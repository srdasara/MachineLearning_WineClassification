# Machine Learning – Wine Classification

I love wine, don't you? Let's have fun with the wine dataset from sklearn.datasets! I will classify wines into 3 different target categories. Let's imagine that these are red wine, white wine, or a rose! 

Here I use the two different **Naive Bayes Classifiers** (notes found here:https://www.quora.com/What-is-the-difference-between-the-the-Gaussian-Bernoulli-Multinomial-and-the-regular-Naive-Bayes-algorithms)

"
* **Multinomial Naive Bayes**: Its is used when we have discrete data (e.g. movie ratings ranging 1 and 5 as each rating will have certain frequency to represent). In text learning we have the count of each word to predict the class or label.

* **Gaussian Naive Bayes**: Because of the assumption of the normal distribution, Gaussian Naive Bayes is used in cases when all our features are continuous. For example in Iris dataset features are sepal width, petal width, sepal length, petal length. So its features can have different values in data set as width and length can vary. We can’t represent features in terms of their occurrences. This means data is continuous. Hence we use Gaussian Naive Bayes here.
"

I also use **Support Vector Machines** https://en.wikipedia.org/wiki/Support-vector_machine: 

"
* a **support-vector machine** constructs a hyperplane or set of hyperplanes in a high- or infinite-dimensional space, which can be used for classification, regression, or other tasks like outliers detection. Intuitively, a good separation is achieved by the hyperplane that has the largest distance to the nearest training-data point of any class (so-called functional margin), since in general the larger the margin, the lower the generalization error of the classifier.

"
