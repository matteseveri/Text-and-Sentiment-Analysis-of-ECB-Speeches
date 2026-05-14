# Text-and-Sentiment-Analysis-of-ECB-Speeches
Authors: Matteo Severi · Gianluca Antonio Spennacchio
Course: Introduction to Python for Economists — University of Bologna

This project applies Natural Language Processing (NLP) and machine learning to a corpus of European Central Bank (ECB) speeches to measure how the tone of monetary policy communication evolves over time.

We build a Hawkish–Dovish (HD) Index by scoring each speech against a dictionary of hawkish terms (e.g. raise, tighten, hike) and dovish terms (e.g. cut, ease, accommodative), handling negations explicitly. The index is then plotted as a time series to reveal shifts in ECB rhetoric from the early Euro years through the post-pandemic tightening cycle. Finally, a Naive Bayes classifier trained on token features validates the sentiment labeling, achieving approximately 87–88% accuracy via K-fold cross-validation.
