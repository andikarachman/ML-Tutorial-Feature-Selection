# Basics of Feature Selection with Python
In machine learning, feature selection is the process of choosing a subset of input features that contribute the most to the output feature for use in model construction. Feature selection is substantially important if we have datasets with high dimensionality (i.e., large number of features). High-dimensional datasets are not preferred because they have lengthy training time and have high risk of overfitting. Feature selection helps to mitigate these problems by selecting features that have high importance to the model, such that the data dimensionality can be reduced without much loss of the total information. Some benefits of feature selection are:
- Reduce training time
- Reduce the risk of overfitting
- Potentially increase model's performance 
- Reduce model's complexity such that interpretation becomes easier

The objective of this notebook is to introduce the fundamental of feature selection in Python. I have tried to keep the notebook as basic as possible so that even newbies can understand every phase of it.  If you think this notebook gives something valuable to your journey to data science, PLEASE UPVOTE. It will keep me motivated.

We will discuss three key methods to perform feature selection together with their implementation in Python:
1. [Filter methods](#section 1.0.)
2. [Wrapper methods](#section 2.0.)
3. [Embedded methods](#section 3.0.)
