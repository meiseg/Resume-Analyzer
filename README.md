


Resume Quality Evaluator

Overview
This project aims to evaluate the quality of resumes using Natural Language Processing (NLP) techniques and a simple neural network built with PyTorch . The program classifies resumes into predefined categories (e.g., "Software Engineer," "Data Scientist") and assigns a quality score based on factors such as keyword relevance, completeness, and clarity.

As someone new to PyTorch , I created this project to deepen my understanding of deep learning frameworks and NLP pipelines. By combining tools like SpaCy for text preprocessing and TF-IDF for feature extraction, this project serves as a stepping stone in my machine learning journey.

Features
Resume Classification :
Predicts the category of a resume (e.g., "Software Engineer") using a neural network trained on labeled data.
Quality Scoring :
Evaluates the quality of a resume based on:
Keyword Coverage : Presence of relevant keywords extracted using SpaCy.
Completeness : Inclusion of essential sections like "Experience," "Education," and "Skills."
Confidence Score : Neural network's confidence in the predicted category.
Support for .docx Files :
Reads resumes from .docx files, preprocesses the text, and evaluates them.
Dynamic Keyword Extraction :
Extracts meaningful keywords for each category directly from the dataset using SpaCy.

Learning Goals
This project was created as part of my learning journey with PyTorch and NLP . Here are some key takeaways:

PyTorch Basics : Building and training a simple neural network for classification tasks.
Text Preprocessing : Using SpaCy for tokenization, lemmatization, and stopword removal.
Feature Extraction : Leveraging TF-IDF to convert text data into numerical features.
Resume Evaluation : Combining multiple metrics (e.g., keyword coverage, completeness) to assess resume quality.
I hope this project inspires others who are new to machine learning and encourages them to experiment with similar ideas!


Future Improvements
While this project provides a solid foundation, there are several ways it can be improved:

Advanced NLP Techniques :
Use embeddings (e.g., Word2Vec, BERT) instead of TF-IDF for better feature representation.
Enhanced Quality Metrics :
Incorporate readability scores, grammar checks, and sentiment analysis.
User Interface :
Build a web-based interface for uploading resumes and viewing results.
Larger Dataset :
Train the model on a more extensive and diverse dataset to improve accuracy.
