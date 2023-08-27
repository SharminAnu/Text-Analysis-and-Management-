You'll work with the UN-Debate dataset for this CA.
1.	Read the dataset as in TextInsight.ipynb discussed in Module 2. Extract the data for the most recent 10 years into a new dataframe. 
Clean the data and generate, for each article, lemmas, nounds, and noun-phrases.
2.	Compute TF-IDF values for lemmas, excluding spaCy stopwords.
3.	Compute TF-IDF values for noun-phrases, excluding spaCy stopwords.
4.	Create a wordcloud image for the top 80 lemmas in the entire corpus. 
Define the score for a lemma in the corpus to be the summation of the tf-idf values of the lemmas with respect to individual documents in the corpus. 
5. Create a wordcloud for the top 50 nouns in the entire corpus. Given below is such a wordcloud image. Your output may show a different layout, but the top 50 nouns should be the same. 
1.	Create a bar graph for the top 20 noun-phrases for the entire corpus. 
Define the score for a noun-phrase to be the summation of the tf-idf values of the nouns contained in the noun-phrase, where a noun-phrase may contain adjectives. 
