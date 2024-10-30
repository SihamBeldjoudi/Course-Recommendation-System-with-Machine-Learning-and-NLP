# Course-Recommendation-System-with-Machine-Learning-and-NLP

This repository contains a machine learning-based recommendation system designed to suggest relevant Udemy courses based on a given course title or description. The system utilizes natural language processing (NLP) and similarity analysis to analyze course content and generate recommendations. Built using libraries such as pandas, neattext, and scikit-learn, the core of the recommendation functionality leverages cosine similarity to measure the relevance between courses.

## Key Features:
- Text Processing: Cleans and standardizes course descriptions using neattext.
- Similarity Analysis: Uses TF-IDF vectorization and cosine similarity to match input descriptions with related courses.
- Data Handling: Manages and processes course data with pandas for efficient storage and retrieval.
- User-Friendly: Input any course title or description to receive a list of similar course recommendations, tailored to your interests.

## Requirements
- Python 3.x
### Libraries Used:
- **pandas**: for data manipulation and analysis.
- **neattext**: for text preprocessing, helping to clean and standardize course descriptions.
- **neattext.functions**: for applying specific text cleaning functions.
- **scikit-learn**:
  - `accuracy_score`, `confusion_matrix`: for model performance evaluation.
  - `train_test_split`: to split data into training and test sets.
  - `CountVectorizer`: for converting text into word count vectors for similarity analysis.
  - `cosine_similarity`: for measuring similarity between course descriptions to drive recommendations.
  - `RandomForestClassifier`: for advanced classification, potentially enhancing recommendation precision.
  - `KNeighborsClassifier`: for course classification using the k-nearest neighbors algorithm.

This combination of libraries supports a robust recommendation system, integrating NLP and machine learning to provide accurate, relevant course suggestions.

