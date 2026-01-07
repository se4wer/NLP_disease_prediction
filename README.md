SYM2DIAG
This project explores Natural Language Processing (NLP) methods for mapping patient symptoms to medical diagnoses. It compares classical word embeddings (PPMI, GloVe) with modern transformer-based models (BERT, ClinicalBERT, FLAN-T5), applying them to the gretelai/symptom_to_diagnosis
 dataset.

The goal is to evaluate different approaches for symptom classification and diagnosis prediction, using metrics such as accuracy, F1-score, and confusion matrices.

Text preprocessing: tokenization, stopword removal, lemmatization (NLTK).

Embeddings:

PPMI (Positive Pointwise Mutual Information)

GloVe (Global Vectors)

Models:

Logistic Regression, Naive Bayes, Random Forest (baseline classical ML).

BERT (bert-base-uncased)

ClinicalBERT (domain-specific variant)

FLAN-T5 (for diagnosis generation).

Evaluation:

Confusion matrices (sklearn & seaborn)

Accuracy, F1-score, ROC-AUC

Word clouds for diagnosis distribution.
