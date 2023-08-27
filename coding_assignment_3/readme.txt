Tasks:
•	Download all news articles from http://web.archive.org/web/20200613003232if_/http://feeds.reuters.com/Reuters/worldNews. 
Use BeautifulSoup to extract, for each news article, the title/headline, the publication time, and the text. 
Store the extracted information into a Pandas DataFrame so that each news article is an entry and the columns include Title, Time, Content.
•	On the above dataset, cleanup the data using the clean and normalize functions and generate, for each article, lemmas, nounds, noun-phrases, and entity pairs. 
Combine them into a dictionary in the following form and save it to a file in a format of your choice: txt, json, csv, pkl:
{"Lemma": [list of lemmas], "Noun": [list of nouns], "Noun Phrase": [list of noun phrases], "Entity Pairs": [list of entity pairs]}
