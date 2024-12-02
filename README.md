# Spelling-Corrector
# ✨ Spelling Corrector - NLP-powered Word Correction System 📚✨

![Python](https://img.shields.io/badge/Python-3.9-blue.svg) ![NLTK](https://img.shields.io/badge/NLTK-Library-green.svg) ![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-orange.svg)

## **Introduction**
Spelling Corrector is an NLP-based project that identifies misspelled words and suggests corrections using probabilistic methods. The tool is built on a foundation of natural language processing and dictionary-based approaches, ensuring robust and accurate word suggestions.

---

## **Features**
✅ **Text Preprocessing**:
- Cleans text by removing stopwords, unwanted characters, and short words.
- Lemmatizes text using WordNet for a normalized representation.

✅ **Word Suggestion Engine**:
- Provides possible corrections for misspelled words based on:
  - Deletions.
  - Insertions.
  - Replacements.
  - Swaps.

✅ **Probabilistic Ranking**:
- Assigns probabilities to suggestions based on word frequencies in the corpus.

✅ **Custom Stopwords**:
- Includes custom stopwords for domain-specific analysis (e.g., "figure", "sample").

---

**How It Works**

1️⃣ Data Preprocessing:
Text data is cleaned and tokenized.
A frequency dictionary and probabilities are computed for all unique words.

2️⃣ Error Detection and Suggestions:
Generate possible corrections for a misspelled word using:

Deletions: Removing one letter.
Insertions: Adding one letter.
Replacements: Replacing a letter.
Swaps: Swapping adjacent letters.

3️⃣ Probabilistic Ranking:
Rank suggestions by their probabilities using a precomputed dictionary.

**Example**

Input:

Misspelled Word: propose

Output:

Suggestions:

propose (Prob: 0.00037)

proposed (Prob: 0.00082)

proposal (Prob: 0.00013)

