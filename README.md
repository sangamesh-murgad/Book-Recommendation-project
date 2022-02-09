# Book-Recommendation-project
Book Recommendation using product similarity

* Business objective

  The objective to build reliable book classification and recomendation engine for a library.

* Data

  Data Was scraped from the goodreads website to mimic the libray with more than 5000 books or different genre. 

* Problems faced

  It was a challage to collect the multiple genre the book belongs to from the website. 
  It was extremly difficlut to classify the book based on the description of the book. Text comprehension by algoritham need humangus data. Embedding the data on your own is a   difficult task
  hence we tried with word2vec, U5 sentence encoder, BERT, to embedd the text. U5 seem to work better meaning reasonable accuracy with less time.

* Models built

  Naive Bayes classification
  U5 sentence encoder - transfer learning and fine tuning
  Recomendation engine
