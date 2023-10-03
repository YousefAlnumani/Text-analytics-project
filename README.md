
My recent project in Text analytics:
The project performs sentiment analysis on Amazon Alexa reviews. It uses Python and various libraries like Pandas for data manipulation and NLTK for natural language processing.
-	Loaded data from "amazon_alexa.tsv" into a DataFrame. The data includes rating, date, variation, review, and feedback.
-	Downloaded natural language processing libraries like "stopwords" and "punkt" from NLTK.
-	Performed various text preprocessing steps like tokenization, lowercasing, and removing stopwords.
-	Created a Word Cloud to examine the most frequent words in the reviews.
-	Utilized the VADER library for sentiment analysis, classifying reviews as positive, negative, or neutral.
-	Plotted a bar chart to show the overall distribution of sentiments.
-	Results indicated 2640 positive, 364 neutral, and 146 negative reviews.
-	Used logistic regression to classify reviews based on sentiment, achieving an accuracy of about 92.5%.
