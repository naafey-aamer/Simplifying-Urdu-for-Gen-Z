# Urdu_to_Roman_Urdu_Transliterator
A neural machine translation task executed with a seq2seq bidirectional LSTM Encoder-Decoder Model with Attention implemented in Keras. Using greedy search for sentence prediction resulted in a BLEU score of 74 and a ROGUE score of 0.90 for medium length sentences 
(10 words < sentence length <=20 words). 

We used bucketing in our work for more specialized, better performing models.

NLP_Data.ipynb is data processing and manipulation.
NLP_Bucket_1.ipynb is the model,predictions, and results for sentences of lengths 0 to 10.
NLP_Bucket_2.ipynb is the model,predictions, and results for sentences of lengths 10 to 20.
NLP_Bucket_3.ipynb is the model,predictions, and results for sentences of lengths 20 to 30.

Reference paper and dataset owners:
https://sci-hub.se/10.1142/s0218001421520017
