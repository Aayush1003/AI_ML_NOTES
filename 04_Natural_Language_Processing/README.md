# Natural Language Processing (NLP)

NLP bridges the gap between human communication and computer understanding.

## 1. Traditional NLP Pipeline
*   **Text Preprocessing:** 
    *   Tokenization (breaking text into words/sentences)
    *   Stopword removal
    *   Stemming & Lemmatization (reducing words to root forms)
*   **Vectorization (Text to Numbers):**
    *   Bag of Words (BoW)
    *   TF-IDF (Term Frequency - Inverse Document Frequency)

## 2. Word Embeddings
Dense vector representations where semantically similar words are closer in space.
*   **Word2Vec:** CBOW and Skip-gram models.
*   **GloVe:** Global Vectors for Word Representation.
*   **FastText:** Uses sub-word information (handles out-of-vocabulary words better).

## 3. Sequence Models in NLP
*   **RNNs / LSTMs:** Historically used for Sentiment Analysis, Machine Translation, and Named Entity Recognition (NER).
*   **Seq2Seq Architectures:** Encoder-Decoder models.

## 4. Modern NLP (The Transformer Era)
*   **Attention Mechanism:** "Self-Attention" allows models to weigh the importance of different words in a sentence simultaneously, completely replacing RNNs.
*   **Transformers (2017):** The architecture behind modern state-of-the-art AI.
*   **BERT (Bidirectional Encoder Representations from Transformers):** Great for text classification, Q&A, and understanding context.
