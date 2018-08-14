# Movie_Sentiment_analysis
This is Kaggle project related to movie review sentiment analysis. The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. There were two files:

<b>Train</b>: which had training data
<b>Test</b>: which had test data

The data can be found on:
https://www.kaggle.com/c/movie-review-sentiment-analysis-kernels-only/data

The sentiment labels are:

0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive

The approach was to use GloVe word embedding as feature and train Bi-directional RNN and Bi-directional RNN-CNN as a model. The deep learning models provide accuracy of arounf 0.68 after 4 epochs. The model loss and accuracy plot indicate inflection point on validation set showing beginning of overfitting. Hence, there are few epochs.

Currently, working on to implement attention models.

# Credits

Nasifur Rahman (https://www.kaggle.com/nafisur)

Parth Rohilla (https://www.kaggle.com/parth05rohilla)
