# Finding Similar Magic: the Gathering Cards Using TF-IDF
This program finds Magic: the Gathering cards that contain similar text to a given card, using sci-kit learn's TF-IDF module.

TF-IDF stands for "Term frequency * inverse document frequency." It is an algorithm for classifying texts based on weighted word counts, where relatively rare words are weighted more heavily than common ones when they appear in a document. Words that appear often in a card's text but rarely in other cards are treated as the most descriptive keywords for that card, while common words are safely ignored. In this way, we can describe a card's text as a vector representing occurrences of each word and their importance to the text, which can then be easily compared to other vectors to find similar cards.

If the CardSimilarity.ipynb Jupyter Notebook file doesn't load in GitHub, try viewing it here: https://nbviewer.jupyter.org/github/ekohrt/MtgSearchSimilarCards/blob/main/CardSimilarity.ipynb

Thank you for checking out my project!
