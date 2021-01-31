<h1 align="center">Day 1: Robust ML Pipeline</h1>

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ_DNf6Q9Ad3iUz90Y9rZ60Ar-PwjdTot_kldJvNtMaipB9koyunJm25QqDLKjIrnIM7lo0WiD4cMlf/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## Exercises
- Open a notebook and download the Titanic dataset
- Make a ColumTransformer having in mind that is for mue
- Train the ColumTransformer (remember is trained on TRAIN data, never on VALIDATION data)
- Export and Load the ColumTransformer in pickle
- Export and Load the ColumTransformer in joblib
- Make a Pipeline with a ColumTransformer and a RandomForestClassifier
- Train the Pipeline with `fit()`
- Export the Pipeline
- Load the Pipeline
- Validate with 10-fold stratifies cross validation
