### Introduction
In 2003, I began a practice of journaling - essentially writing down my thoughts, plans, fears, and introspections into a simple text file. It's been sporadically updated (at least once a month) until the present day. Journaling is an invaluable tool to better understand one's own mind: to analyze decision making patterns, identify trends, and find purpose in this confusing world. 

Over the years, I've conducted plenty of informal, manual deep-dives into my journal. For example, when recovering from an injury, I used my journal to identify triggers that caused aggravation and plotted those over time to better understand how my recovery process was being shaped by my behavior. What if there was a way to do this analysis programmatically? Luckily, there is - it's called Natural Language Processing - and there are plenty of libraries that allow us to parse and analyze vast amounts of text! 

We will use TextBlob, a popular python NLP library, to answer some of the following questions:

- Summary stats - words/ year, entries/ year, overall words
- Most common words and combinations of words using word clouds.
- Parts of Speech tagging (Noun, verb, adjective)
- Phrases over the years using popular combinations of words
- Sentiment analysis - how has the tone (positive/negative) changed over time?
- Train our own sentiment analyzer and compare results with the built-in Naive Bayes classifiers
