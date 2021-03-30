# Authorship-Attribution

Use Jupyter nbviewer if you have trouble rendering the ipynb file, i.e. copy the ipynb link into nbviewer https://nbviewer.jupyter.org/

Given a piece of work, how do we identify its author? This piece of work aimed to give a brief idea on authorship attribution using Markov Chain.

Authorship attribution (AA) is the task of identifying the author of a given text. It should not be confused with Authorship Profiling that concern with the author’s information such as age, gender or ethnicity. It is a natural processing language classification problem.

In this github, stylometry features from the train and test text has been extracted in the form transition matrices. 
Four different similarity measurement including log-likelihood, KL divergence, JS divergence and LDA had been proposed.
Bagging ensemble model with majority voting had been used to improved the performance.

We also demonstrated techniques to handle characters that only missing in the training set, such as grouping and smoothing.
In addition, we also experiment with different Markov Chain order.
As a result, the model can give n accuracy of 93% and F1 score of 0.9.

Alternatively, a simple AA using log-likelihood is demonstrated and published at Medium
https://tengliyuan1988.medium.com/authorship-attribution-through-markov-chain-922b01a40920
