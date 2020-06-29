Name Entity Recognition model with Multi-head Attention Seq2Seq Model (for medical statements)

Running Environment: Colab, with GPU running time type

Model library: Tensorflow.Keras

Classic Model Archietecture Reference: Seq2seq, Transformer

To run the code, you should firstly upload train.csv and test.csv onto colab platform.
The relative dataset can be downloaded from:
https://www.kaggle.com/aggarwalayush775/innoplex
The project is set up using this data, thanks for its author(s) and the doctors' statements

If you would like to predict your own dataset, you should name your dataset as test.csv,
and ensure your dataset's format is the same with the original test.csv
(Format: Second column for Doc id, third column for Sentence id, and forth column for each single word)

There are several modules in code:

  Parameters Setting - tuned Parameters, change it for your convenience

  Preprocess - Sequence and labels' embedding

  Seq2seq Model with Multi-head Attention - Model build-up and fitting

  Evaluation - Visualisation of model fitting, and some evaluation indices
  
  Prediction - Prediction on test set

Generated docs: train model, encoder model, decoder model, predicted testset result

More details can be viewed in comment line descirptions and Visualisation parts in code
