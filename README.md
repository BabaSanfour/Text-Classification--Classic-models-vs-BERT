
In this notebook we have a copmarison between 4 classic ML models from different families (LogReg using L2 and L1, RandomForest and XGboost) and a transofomer: Bidirectional Encoder Representations from Transformers. Comparison was done using accuracy and ROC AUC, a two popular metrics in the machine learning field.

For the classic models, we used TF-IDF to generate tokens and train the models.

For BERT, we used the pretrained version provided by huggingface: BERTforSequenceClassification.

The task was binary classification of positive vs negative reviews on the famous IMDB movies dataset
The IMDB Reviews data can be downloaded from here: http://ai.stanford.edu/~amaas/data/sentiment/.

At the end we also added some attention weights for the BERT heads visualization using heatmaps
