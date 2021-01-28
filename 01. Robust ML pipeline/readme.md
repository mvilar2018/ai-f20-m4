<h1 align="center">Day 1: Robust ML Pipeline</h1>

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