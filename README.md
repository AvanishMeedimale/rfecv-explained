# rfecv-explained
Recursive Feature Elimination Cross Validation (RFECV) is a useful dimensionality reduction technique that removes unimportant features that lower the accuracy of your model, and thus makes a simpler model that will be less prone to overfitting. I have seen many Kagglers implement it through sklearn's RFECV class, but there is a lack of deeper understanding beyond knowing it picks out an optimal subset of features to be fed into your model. This will create situations where RFECV may produce misleading results, or less flexibility while data modelling as you don't know what is actually going on. This isn't helped by the fact the documentation provided is also pretty vague on how exactly this method works.

This repo is split into three seperate notebooks:

1. Building up the RFECV technique from scratch
2. The limitations of the RFECV method (Decision Trees)
3. How correlated features impact the technique
