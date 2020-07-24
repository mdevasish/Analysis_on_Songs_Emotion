# Analysis_on_Songs_Emotion
Topic Modelling, Sentiment Analysis, Document Retrieval based on emotion of the song

This project is taken up for educational purposes.

The dataset for our project was sourced from Kaggle, titled ‘Every song you have heard (almost)!’ (Agarwal, 2017). This dataset comprises 2 files, each containing approximately 250,000 songs with their artists and lyrics and song titles. In total, we have over 500,000 song lyrics at our disposal. Below are the usecases implemented on this repo:

a.	Analytics task 1 - Document retrieval
Type in a search phrase, say “girls like you”. Retrieve all relevant songs about the search phrase from the dataset. 

Task is to retrieve the songs based on a simple search by the lyrics of the song or artist. The playlist of a user can also be predicted by the tracks listened by the user. The method of document retrieval is based on cosine similarity and based on the cosine similarity score the documents are ranked. 
If the query keyed in is an artist name, a simple filter on the list of artists will be conducted and all the list of songs associated with the artist are retrieved. 
If the query is about the song cosine similarity is used to retrieve the documents.

b.	Analytics task 2 - Sentiment analysis
Sentiment analysis to understand the sentiment behind the song: happiness? Sadness? Etc

c.	Analytics task 3 - Topic analysis
Topic analysis to find out the major themes covered by the songs
