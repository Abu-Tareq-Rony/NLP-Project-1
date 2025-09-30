# NLP Project 1 — QTL Terminology Mining

Analyze QTL abstracts, build word clouds (frequency + TF-IDF), train Word2Vec, extract phrases (Gensim bigram+trigram, NP-chunking), and exact-match phrases to a trait dictionary.

## Setup
```bash
python -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate
pip install -U pip
pip install nltk gensim scikit-learn wordcloud
