# Named-Entity-Recognition
Kaggle NER dataset: https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus

This solution consists of a MLP using two words as context, so each word will be used as [prev_word, word, next_word].

This tripplet of words is then fed into a MLP with a single Dense layer.

It achieved a 98.78% score.
