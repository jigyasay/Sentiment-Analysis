# Sentiment-Analysis
Movie Review Sentiment Analysis
Tools & Technologies: Python, NLTK, scikit-learn, pandas

Objective: Developed a sentiment analysis model to classify movie reviews as positive or negative using the NLTK Movie Reviews Corpus.

# Data Collection:

Utilized the NLTK library to access the Movie Reviews Corpus, containing 2,000 labeled positive and negative movie reviews.
Extracted and prepared the data by loading reviews and their respective categories from the corpus.

# Data Preprocessing:

Implemented text preprocessing techniques to clean and prepare the reviews for analysis.
Tokenized text into words, converted to lowercase, and removed non-alphabetic characters.
Filtered out common stopwords and punctuation to enhance model performance.
Utilized pandas to organize and manipulate the dataset efficiently.

# Feature Engineering:

Applied CountVectorizer and TfidfVectorizer from scikit-learn to convert textual data into numerical features suitable for model training.
Explored different vectorization techniques to find the best representation of text data for the classifier.

# Model Training:

Split the dataset into training and testing sets to evaluate model performance.
Trained a Multinomial Naive Bayes classifier using the training data.
Leveraged scikit-learn's MultinomialNB to develop the sentiment analysis model.

# Model Evaluation:

Assessed the model's performance using accuracy metrics.
Achieved an accuracy of 85% in predicting the sentiment of movie reviews.
Results:

Successfully classified movie reviews with an accuracy of 85%, demonstrating strong performance in sentiment analysis.
Provided valuable insights into the effectiveness of different preprocessing and vectorization techniques in natural language processing tasks.
