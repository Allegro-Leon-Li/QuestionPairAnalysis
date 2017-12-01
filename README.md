# QuestionPairAnalysis
This is the CS 506 project directory

## Datasets
Datasets are named `train.csv` and `test.csv` which must be put in the current dir. Those files can be downloaded from Kaggle website at: https://www.kaggle.com/c/quora-question-pairs/data

## Requirement

1. **Word2Vec**: The pre-trained Word2Vec(find the "pre-trained word and phrase vectors" at https://code.google.com/archive/p/word2vec/) should be placed in the current directory in the name of `GoogleNews-vectors-negative300.bin.gz`
2. **gensim**: For loading Word2Vec. Search Google for how to install (should be installed by `pip install` normally)
3. **XGBoost**: For classification, the install process should follow the instructions at http://xgboost.readthedocs.io/en/latest/build.html
