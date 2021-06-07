# Tweet Sentiment Analysis

1. Physolophy

Write a Python script to check the “Getting to Philosophy” law.
https://en.wikipedia.org/wiki/Wikipedia:Getting_to_Philosophy

Clicking on the first link in the main body of a Wikipedia article and repeating the process for subsequent articles would usually lead to the article Philosophy.

The program should receive a Wikipedia link as an input, go to another normal link and repeat this process until either the Philosophy page is reached, or we are in an article without any outgoing wiki links or stuck in a loop.

A “normal link” is a link from the main page article, not in a box, is blue (red is for non-existing articles), not in parentheses, not italic, and not a footnote. You don’t have to check style tables or other fancy things, it is enough that the script works with the current Wikipedia style (for example you can use the ‘class’ attribute in Wikipedia tags). For easy validation, please print all visited links to the standard output.

Use a 0.5-second timeout between queries to avoid heavy load on Wikipedia.

You can use https://en.wikipedia.org/wiki/Special:Random for testing.

2. Sentiment Analysis

Create a Jupyter notebook with a simple analysis based on Twitter Sentiment Analysis Training Corpus:
http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/
— Show the top-10 most positive words, top-10 negative words (words more frequent with positive and negative labels respectively). 
— Check the Zipf law (https://en.wikipedia.org/wiki/Zipf%27s_law: the frequency of any word is inversely proportional to its rank in the frequency table), show it using a plot. 
— Write a simple classifier to predict sentiment, describe your approach, and what can be done to improve the results.
