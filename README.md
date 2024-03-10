# Feature Selection: RFECV Explained
Recursive Feature Elimination Cross Validation (RFECV) is a useful dimensionality reduction technique that removes unimportant features that lower the accuracy of your model, and thus makes a simpler model that will be less prone to overfitting. I have seen many Kagglers implement it through sklearn's RFECV class, but there is a lack of deeper understanding beyond knowing it picks out an optimal subset of features to be fed into your model. This will create situations where RFECV may produce misleading results, or less flexibility while data modelling as you don't know what is actually going on. This isn't helped by the fact the documentation provided is also pretty vague on how exactly this method works.

This repository is split into three seperate notebooks. The first explains the core concept and functionality of the technique, with the next two exploring more nuances and drawbacks of the technique:

1. [Building up the RFECV technique from scratch](building-rfecv-from-the-ground-up.ipynb)
2. [The Limitations of the RFECV method (Decision Trees)](tree-based-drawbacks.ipynb)
3. [How do correlated features impact this technique?](handling-correlated-features.ipynb)
