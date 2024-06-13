![machine-learning-healthcare-blog-hero](https://github.com/sehaj003/Disease-Prediction-NLP/assets/154620160/f1081f8a-3382-4468-855c-ec02653d1c45)
# Disease-Prediction-NLP
Disease prediction based on drug reviews.

This project utilizes Natural Language Processing (NLP) techniques to predict medical conditions based on patient reviews of drugs. The model aims to classify the condition for which the drug was prescribed by analyzing textual reviews.

## Dataset

The dataset used for this project is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/462/drug+review+dataset+drugs+com). It includes patient reviews on specific drugs, associated conditions, and a 10-star rating reflecting overall satisfaction.

- **Columns:**
  - `drugName` (categorical): Name of the drug.
  - `condition` (categorical): Name of the condition.
  - `review` (text): Patient review.
  - `rating` (numerical): 10-star patient rating.
  - `date` (date): Date of review entry.
  - `usefulCount` (numerical): Number of users who found the review useful.
 
## Methodology

1. Data Loading and Exploration:
   * The dataset is loaded using pandas.
   * Initial exploration of the data to understand its structure and content.

2. Data Preprocessing:
   * Handling missing values.
   * Text cleaning (removing punctuation, lowercasing, etc.).

3. Feature Extraction:
   * Using CountVectorizer and TfidfVectorizer to convert text data into numerical features.

5. Model Training:
   * Splitting the data into training and test sets.
   * Training models such as PassiveAggressiveClassifier and MultinomialNB.

7. Evaluation:
   * Evaluating the models using metrics such as accuracy, precision, recall, and F1-score.
   * Visualizing the results using seaborn and matplotlib.

## Results
The models were evaluated on their ability to predict the condition based on drug reviews. Below are the accuracy scores for different models:

1. Bag of Words - Accuracy: 0.970
2. Passive Aggressive Classifier with Bag of Words - Accuracy: 0.977
3. TFIDF Model - Accuracy: 0.982
4. Naive Bayes with TFIDF - Accuracy: 0.921
5. TFIDF Bigrams - Accuracy: 0.986
6. TFIDF Trigrams - Accuracy: 0.985

## About Me
My Name is Sehaj Malhotra I'm a graduate student at Northeastern University, pursuing my master's in Data Analytics Engineering. I have a strong passion for Data Analytics, Data Visualization, and Machine Learning. I am an aspiring Data Analyst/Data Scientist. I love working with data to extract valuable insights.

MY LINKEDIN: https://www.linkedin.com/in/sehajmalhotra/

MY KAGGLE: https://www.kaggle.com/sehaj2001
