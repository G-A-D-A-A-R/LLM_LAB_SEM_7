# LLM_LAB_SEM_7

Repository containing all practical assignments, laboratory exercises, and code implementations for the **Introduction to Large Language Models (ILLM)** course in Semester 7.

---

## 📚 Laboratory Practical Overview

| Lab Directory | Topic / Assignment | Key Concepts & Techniques |
| :--- | :--- | :--- |
| **`LLM_LAB_1_30_07_26`** | Language Identification (LID) | IndicCorp dataset, character n-grams, text pre-processing, Naive Bayes / linear classifiers |
| **`LLM_LAB_2_06_08_26`** | TF-IDF & Text Normalization | TF-IDF feature extraction, sublinear scaling, document normalization, classification benchmarks |
| **`LLM_LAB_3_13_08_26`** | Subword Tokenization (BPE & WordPiece) | Byte Pair Encoding (BPE) & WordPiece algorithms from scratch, vocabulary size sweeps on Hindi Devanagari |
| **`LLM_LAB_4_20_08_26`** | N-Gram Language Modeling & Smoothing | N-gram language models, Laplace (Add-1), Add-$k$, Jelinek-Mercer interpolation, perplexity evaluation |
| **`LLM_LAB_5_27_08_26`** | Word & Document Embeddings | Word2Vec (Skip-gram, CBOW), FastText, Doc2Vec, semantic similarity, KMeans clustering |
| **`LLM_LAB_6_03_09_26`** | FastText & Scalable LID Classifiers | Supervised FastText classification, hyperparameter tuning, multi-class multilingual evaluation |
| **`LLM_LAB_7_10_09_26`** | Hidden Markov Models (HMM) & Chunking | HMM sequential tagging, Viterbi decoding algorithm, Noun Phrase (NP) chunking |
| **`LLM_LAB_8_01_10_26`** | Neural Machine Translation with OpenNMT | OpenNMT-py seq2seq models, vocabulary preparation, model training & checkpoints, sacreBLEU evaluation |
| **`LLM_LAB_9_08_10_26`** | Transformer NMT & Seq2Seq Models | PyTorch Transformer architecture, multi-head attention, positional encoding, bilingual translation |
| **`LLM_LAB_10_15_10_26`** | Fine-Tuning BERT for Language Identification | Hugging Face Transformers, sequence classification fine-tuning, evaluation metrics & error analysis |
| **`LLM_LAB_11_22_10_26`** | Probing BERT Layer Representations | SentEval probing tasks (Sentence Length, Bigram Shift, Subject Number), layer-wise representation analysis |

---

## 🛠️ Tech Stack & Libraries

- **Deep Learning & NLP**: PyTorch, Hugging Face Transformers, OpenNMT-py, FastText, Gensim, Scikit-learn, NLTK
- **Evaluation & Metrics**: SacreBLEU, Seqeval, Scikit-learn metrics
- **Environments**: Jupyter Notebooks (`.ipynb`), Python 3.10+

---

## 📂 Repository Structure

```
LLM_LAB_SEM_7/
├── LLM_LAB_1_30_07_26/      # Lab 1: Language Identification
├── LLM_LAB_2_06_08_26/      # Lab 2: TF-IDF Normalization
├── LLM_LAB_3_13_08_26/      # Lab 3: BPE & WordPiece Tokenization
├── LLM_LAB_4_20_08_26/      # Lab 4: N-Gram Smoothing
├── LLM_LAB_5_27_08_26/      # Lab 5: Word & Document Embeddings
├── LLM_LAB_6_03_09_26/      # Lab 6: FastText LID Classifiers
├── LLM_LAB_7_10_09_26/      # Lab 7: HMM NP Chunking
├── LLM_LAB_8_01_10_26/      # Lab 8: OpenNMT Translation
├── LLM_LAB_9_08_10_26/      # Lab 9: Transformer NMT
├── LLM_LAB_10_15_10_26/     # Lab 10: BERT Fine-Tuning
├── LLM_LAB_11_22_10_26/     # Lab 11: BERT Layer Probing
├── .gitignore
└── README.md
```
