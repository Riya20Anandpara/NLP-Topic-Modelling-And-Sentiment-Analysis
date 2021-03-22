# NLP-Topic-Modelling-And-Sentiment-Analysis

Introduction
Natural Language Processing is a Machine Learning method used to teach computers how to understand natural human language. It is not an easy task to teach these languages to a computer, but with the help of NLP process it's possible for the computer to read, decipher, understand, and make sense of the human languages in a manner that is valuable.

In machine learning and natural language processing, a topic model is a statistical model used for discovering the abstract "topics" that occur in a collection of documents or in a corpus. A topic is a collection of dominant keywords that express the general meaning of the text.

NLP could be used to

extract topics from reviews, social media feeds, comments, articles, emails as well as user feedbacks. Understanding what customers are talking about in a particular product is very vital to companies especially e-commerce industry. However, since these online reviews are quite often overwhelming in terms of numbers and information, an intelligent system, capable of finding key insights (topics) from these reviews, will be of great help for both customers and companies.

The goal of my project is to help Nissan cars increase the brand value using analysis.

One of the most effective ways of doing topic modeling is by using Gensim LDA model. In this project we will be using the following 2 versions of gensim LDA model to see which one is the fastest computationally, provides meaningful topics and has the best coherence score:

LDAMulticore
LDAMallet

Tools and Libraries used
NLTK (Words tokenizer, stopwords and WordNetLemmatizer)

Spacy
Seaborn and Matplotlib
Gensim libraries for Topic modeling
TextBlob (sentiment analysis library)
Pickle
WordCloud
Plotly
Numpy and Pandas
PyLDAViz


Project Process
Pre-processing
Remove null-values i.e rows with no reviews
Drop some unwanted columns
Do some feature engineering
Change the data type of some of the columns like date column
Remove stop-words with NLTK
Remove number from text with regular expression function
Lower the text and remove words lower than 3 letters
Bring the text back to it's base via lemmatization with Spacy
EDA
Do some visualization, e.g wordcloud to uderstand the common words in the review
LDA Model fitting for topic modeling
Create a dictionatry and a corpus with the review text (the 2 are needed for the LDA models)
Try out the 2 LDA models (LDAMulticore and LDAMallet) to see the one with the highest coherence score and with meaningful topics from the text
Sentiment Analysis
Do some feature engineering to get the sentiment in the reviews
Used TextBlob to derive the polarity and subjectivity in the reviews
Visualization
Plot the the topics PyLDAviz
Use both plotly and Tableau to visualize the result of the sentiments
Communicate insights
Conclusion
Future work to improve the project

