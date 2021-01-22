# spam_classifier
Imports training data as a csv file with columns such as one being the message another a label

Eliminates non alpha numeric characters and breaks sentence into works using nltk librariries. Chooses ngram and eliminates stopwords.

gets word frequency aka. term frequency
calculates probablity of word existing in both spam and non spam messages using bayes algorithm
sets cutoff at .5 and if spam is greater than .5 then classified as spam
