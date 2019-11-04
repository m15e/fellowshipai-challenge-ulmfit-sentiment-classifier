## Fellowship.ai Challenge: ULMFiT applied to the Twitter US Airline Sentiment dataset

## Transfer learning is no longer limited to computer vision

Universal Language Model Fine-tuning (ULMFiT), a novel approach towards applying transfer learning to natural language processing tasks, was originally introduced by Jeremy Howard and Sebastian Ruder in early 2018.  

Transfer learning is a method that takes advantage of models that have already been pre-trained to learn a given task on large datasets and re-purposes them to learn a (new) related task. This dramatically reduces the amount training data and time needed to train a model.

Howard and Ruder demonstrated that transfer learning, which had previously only been successful with computer vision problems, can be applied to natural language processing tasks as well. At the time of ULMFiT's initial release, it outperformed the state-of-the-art on six text classification benchmarks. 

<strong>Classifying the sentiment of tweets</strong>

This is a documented attempt at creating an ULMFiT model that can correctly classify the sentiment of tweets from from the [Twitter US Airline Sentiment dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment). The data consists of 14640 labeled tweets directed at six major US airline companies (Virgin America, United, Southwest, Delta, US Airways and American Airlines). We will train a model to identify whether the tweets are positive, neutral or negative. 

The Twitter US Airline Sentiment dataset is available [here](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)

[Click this link](https://www.kaggle.com/marklv/fellowship-challenge) to read the full report on Kaggle.

References:

[Original ULMFiT Paper by Jeremy Howard and Sebastian Ruder](https://arxiv.org/abs/1801.06146)
