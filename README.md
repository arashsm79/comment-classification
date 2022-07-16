# Comment Classification using NLP techniques
> Classifying Reddit comments that are about physics, chemistry and biology using NLTK
  - First, we preprocess the corpus using regex and nltk's tokenization and lemmatization
  - Then we use word2vec to create a representation for each word
  - after that, we cluster the representations in order to find the words that are close together in terms of their meaning
  - We then replace all the worlds of each cluster with the representative word of that cluster in the corpus. (this effectively makes sure that all the words in a cluster take the same spot in the bag of words vector).
  - Finally, we create a representation for each comment using bag of words and TF-IDF and try to classify the test data set.
