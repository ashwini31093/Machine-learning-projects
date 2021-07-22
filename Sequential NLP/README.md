PART 1:

AIM: Predict customers' sentiments for IMDB dataset by building and tuning a sequential NLP

Jupyter NB: IMDB_SentimentAnalyis_Sequential

Actions perform:

1.Import and analyse the data set.Take 10000 most frequent words
2.Perform relevant sequence adding on the data
3.Perform following data analysis.
      Print shape of features and labels
      Print value of any one feature and it's label
4.Decode the feature value to get original sentence
5.Design, train, tune and test a sequential model.
6.Use the designed model to print the prediction on any one sample.


PART 2: 

AIM: Detect sarcasm for headlines by training and tuning a Bidirectional LSTM model on New headlines for Sarcasm detection data.

Jupyter NB: Sarcasm_Detection
Dataset : Sarcasm_Headlines_Dataset.json 

Actions perform:

1.Import and analyse the data set.Take 10000 most frequent words
2.Read and explore the data. Retain relevant columns
3.Get length of each sentence
4.Define parameters
5.Get indices for words
6.Create features and labels.Split them into 70:30 train-test ratio
7. Create a weight matrix using GloVe embeddings
8. Define , compile and fit a Bidirectional LSTM model.Check the validation accuracy
