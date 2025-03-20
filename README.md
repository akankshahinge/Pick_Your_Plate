# Pick_Your_Plate
Restaurant Data Analysis for Sentiment Prediction

#### Business Problem
Resturants receive thousands of reviews online. Manually analyzing these reviews to extract insights is time-consuming and inefficient. Automate the analysis of customer reviews using Natural Language Processing and then classify the reviews as Positive or negative sentiment. This will provide actionable insights to help resturants improve service quality and customer satisfaction.

#### Text Preprocessing
1. Tokenization: Split reviews into individual words using NLTK word_tokenizer.
2. Stopword Removal: Eliminated common English words using NLTK.
3. Stemming: Normalized words to their root forms using Porter Stemmer.
4. Emoji and Punctuation Removal: Removed emojis, punctuation, and special characters to enhance text clarity.
5. N-grams Extraction: Captured frequent single words, bigrams, and trigrams. ngram_range=(1,3).
6. TF-IDF Vectorization: Converted textual data into numerical vectors for SVM modeling.
