# nlp-fake-news

### Assignment Instructions
Classification problem of News Report (document) for classes (FAKE, REAL). Try text-related classifiers such as Naive Bayes, MaxEnt, SVM. Use NLTK+SKLearn, NLP Pre-processing, Classifiers and CV-evaluation.

### Dataset
**fake_or_real_news_training:**
- ID: ID of the tweet
- Title: Title of the news report
- Text: Textual content of the news report
- Label: Target Variable (FAKE, REAL)
- X1, X2 additional fields

**fake_or_real_news_test:**
- ID, title and text
- Predict Label

### Project Plan
**Section 1:**
1. Variable analysis
  - Features
  - Other insight
2. Data Processing
    - Drop features
    - Label,
3. Baseline Models
    - Navie Bayes
    - MaxEnt (not working -> config issues -> unresolved)
    - SVM

**Section 2:**
1. POS Tagging
2. POS Model

**Section 3:**
1. Bag of Words Approaches
2. Model Optimization

**Section 4:**
Please note this section uses gloVe6b.50.txt file for embedding. Please download: https://nlp.stanford.edu/projects/glove/
1. Kears Models
    - Seqential NN
    - CNN
    - LTSM w. Embeddning


**Section 5:**
1. Ensamble
2. Final Prediction
3. Submission
