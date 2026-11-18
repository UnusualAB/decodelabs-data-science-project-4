Project 4: NLP & Sentiment Analysis


Description
This project focuses on building a complete Natural Language Processing pipeline to classify movie reviews as Positive or Negative. The main goals are:

- Building a robust text pre-processing pipeline
- Converting unstructured text into numerical features using TF-IDF
- Training and comparing Naive Bayes and SVM classifier

Dataset
- Source: IMDB Movie Reviews Dataset
- Total Reviews: 50,000
- Classes: 25,000 Positive + 25,000 Negative (perfectly balanced)



# How to Run
# Requirements
```bash
pip install pandas numpy scikit-learn nltk

Steps
1. Place IMDB Dataset.csv in the same folder as the notebook.
2. Open the Jupyter Notebook.
3. Run all cells from top to bottom.
4. Final selected model: SVM (LinearSVC)



Project Workflow
1. Data Exploration
    50,000 reviews, perfectly balanced, no missing values

2. Text Pre-processing Pipeline
    Removed HTML tags
    Removed special characters and numbers
    Converted to lowercase
    Tokenization
    Stop-word removal
    Lemmatization

3. Feature Extraction
    Applied TF-IDF Vectorizer (max 5,000 features)

4. Model Training
    Multinomial Naive Bayes
    Linear Support Vector Machine (SVM)

5. Evaluation
    SVM outperformed Naive Bayes