Text Summarization with Python
Overview
This project demonstrates a simple text summarization technique using Python. The goal is to automatically summarize a given text by extracting the most important sentences. The project uses Natural Language Processing (NLP) techniques to process and summarize text from a Wikipedia article. The summarization process involves web scraping, text cleaning, sentence tokenization, word frequency analysis, and sentence scoring.

Features
Web Scraping: Fetches content from a Wikipedia page using urllib.request and BeautifulSoup.

Text Cleaning: Removes unnecessary characters, numbers, and reference numbers from the text.

Sentence and Word Tokenization: Splits the text into sentences and words using the nltk library.

Stopwords Removal: Filters out common stopwords (e.g., "and", "the") to focus on meaningful words.

Word Frequency Analysis: Calculates the frequency of each word and normalizes the frequencies.

Sentence Scoring: Scores sentences based on the frequency of the words they contain.

Summary Generation: Selects the top sentences with the highest scores to create a summary.
