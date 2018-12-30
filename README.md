# ToxicCommentClassification
Toxic comment classification using Machine learning
The goal of this project is to classify wikipedia comments into six classes of toxicity: toxic, severe toxic, obscene, threat, insult and identity hate. 

Project package should contain below files:
-train.csv
-test.csv
-test_labels.csv (these three files can be downloaded from https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data )
-ToxicCommentClassification.py
-glove.twitter.27B.50d.txt (this file can be downloaded from https://nlp.stanford.edu/projects/glove/ )

The training dataset file is named train.csv, test dataset file is named test.csv and the actual labels are in test_labels.csv file. GloVe pre-trained embeddings required for the project is in the glove.twitter.27B.50d.txt.

Please place all the five files in a single directory

Module downloads
------------------------------
Download commands for some modules required that may not already be present in the target system is included in the source file. 
If there are errors for missing modules, please install the same using following command from jupyter notebook:

!pip install [module name]

or using this command in the .py file:
get_ipython().system('pip install [module_name]')

Execution steps
------------------------------
Once all of the required files and modules are downloaded and placed in the same folder as the source code file, we can execute the ToxicCommentClassification.py to run the project.

