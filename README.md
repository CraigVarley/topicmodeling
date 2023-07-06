# topicmodeling

Using Python libraries to topic model library chat transcripts 2013-2023. This is private right now due to info in the csv. Will eventually post the cleaned csv here.

This takes a csv file of ~6500 chats from LibraryH3lp covering 10 years or so of interaction between librarians and patrons.

I use the standards Python libraries (Pandas, Matplotlib, NLTK, SciKit):

  - to preprocess the text (lemmatize, anonymize, lowercase, remove urls and system messages)
  - run it through a topic modelling algorithm (LDA) with 5 topics
  - create a function at the end that loops the cleaned text thorugh a range of topic numbers (4-20) then evaluates their coherence and graphs it


Skip to the end to see the final looping function that also evaluates the coherence. Earlier functions clean the text and there are some very ugly regex cleaning bits earlier on.

It's all very ugly but the result is fun.
