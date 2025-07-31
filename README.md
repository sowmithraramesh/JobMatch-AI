# Resume Classifier using NLP & Machine Learning

A simple Natural Language Processing (NLP) project that classifies resumes into predefined job categories using spaCy for text preprocessing, TF-IDF for feature extraction, and Logistic Regression for classification.


## Features

- Resume preprocessing using spaCy:
  - Tokenization
  - Lowercasing
  - Stopword Removal
  - Lemmatization
- TF-IDF Vectorization
- Logistic Regression Classifier
- Predicts job category based on resume text
- Evaluation with accuracy score and classification report


## Technologies Used:

- Python 3.x
- spaCy (`en_core_web_sm`)
- Scikit-learn (sklearn)
- Pandas
- NumPy



## Project Structure:
resume-classifier/
├── dataset.csv # Resume texts with categories (user provided or sample)
├── resume_classifier.py # Main script to run training and prediction

## Output:
<img width="899" height="363" alt="image" src="https://github.com/user-attachments/assets/f87049f3-c14b-49ed-8d86-5fab15830468" />
