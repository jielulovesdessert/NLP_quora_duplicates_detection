# NLP_quora_duplicates_detection

Customized siamese LSTM to solve the duplicate detection challenge 

It is generally considered challenging to decide whether two questions are intended to ask the same content, because there are a variety of choices of words and sentence structures. I used the dataset launched by Quora for this task, the well-known question-and-answer platform. The dataset consists of 400K+ labelled question pairs. I referred to the architecture of the academia benchmark - Siamese LSTM, while implementing my own LSTM structure to tackle this problem, and reached a competitive score. A major focus of this project is on the hyperparameter tuning. I tuned some major hyperparameters, made a thorough comparison and yielded the best available model under my experimental setting. Moreover, the deep learning techniques significantly outperform traditional statistical learning baseline.

[Please view the full report here.](https://github.com/jielulovesdessert/NLP_quora_duplicates_detection/blob/master/Quora%20Project%20Report.pdf)

Jupyter Notebook Functions:

| Notebook       | Functions          | 
| ------------- |:-------------:|
| Data Preprocessing.ipynb     | cleaning + GloVe Embedding |
| Quora EDAV + Benchmark.ipynb    | EDAV + plotly + XGBoost     |
| LJ LSTM Modelling.ipynb | customized siamese LSTM    |
| Model Experiment.ipynb | Hyperparameter Tuning |
