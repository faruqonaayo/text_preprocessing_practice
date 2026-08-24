# Hotel Review Text Preprocessing & N-Gram Analysis

This project applies **Natural Language Processing (NLP)** techniques to analyze TripAdvisor hotel reviews.

## 🛠️ Technologies

* Python
* Pandas
* NLTK
* Regex
* Matplotlib

## 🔄 Text Preprocessing

The reviews were cleaned and transformed through:

1. **Lowercasing** – converted text to lowercase.
2. **Stopword Removal** – removed common English stopwords.
3. **Punctuation Removal** – cleaned punctuation and converted `*` to "star".
4. **Tokenization** – split reviews into individual words.
5. **Stemming** – reduced words to their root form using Porter Stemmer.
6. **Lemmatization** – converted words to their meaningful base form.

## 📊 N-Gram Analysis

The processed reviews were analyzed using:

* **Unigrams** – individual words
* **Bigrams** – two-word combinations
* **Trigrams** – three-word combinations

Bar charts were created to visualize the **top 10 most frequent unigrams, bigrams, and trigrams**, providing an overview of common words and phrases in the reviews.

## 🎯 Goal

To practice fundamental NLP preprocessing techniques and identify common patterns in hotel reviews through **N-gram frequency analysis**.
