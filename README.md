# Understanding Depression in Social Media
Sentiment analysis is a very popular technique to determine the emotional tone of text data.
In cases I have seen often, sentiment analysis was not able to capture what someone may have been feeling at a deeper level. This is especially more important in cases of mental health. Sentiment analysis is typically used for customer support, reviews, etc. With this notebook, I am looking to capture emotions felt by users online when they write text on the topic of depression.

I used Cohere's `multilingual-22-12` model and `embed` function to create embeddings and predict the probability of each emotion for multiple languages. It worked seemlessly and was very easy to use. In the future, I hope to use a Production API key.

Apart from the sentiment analysis, the current notebook was to get an introductory feel to Cohere's capabilities. On a personal viewpoint, I agreed with a lot of the predictions of emotion classifications on the input text, which I was impressed by.

This is a project I hope to expand upon in the future, where I would create my own model and carry out further data analysis on the combined emotion + input texts dataset.
