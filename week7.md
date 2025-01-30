# Week 7 Report: Challenges faced

What challenges has been faced?

A notable problem I faced during this study was the hardware constraints of my laptop that affected my use of Hugging Face’s transformer-based models. In particular, models like BERT, RoBERTa, and DistilBERT for sentiment analysis from Hugging Face utilise a large amount of power, especially in the form of GPU acceleration, to perform any sort of text processing. Given the age of my laptop and its subpar GPU, these models were extremely slow to use and often resulted in system crashes.

Several times, my laptop was unable to load and use the transformer models which severely impeded Agreggation’s ability to predict sentiments and generate embeddings. This was mostly a problem with large datasets where the system memory was excessively high, leading to the system freezing or becoming completely unresponsive. On top of this, as text is processed in batches by deep learning models, the low amounts of available RAM on my laptop forced me to reduce batch sizes, resulting in even greater lags and further inefficiencies.
