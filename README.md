# Spam-Messages-Detection-NLP
This Python project demonstrates a machine learning pipeline for SMS spam detection using text preprocessing and classification techniques. The workflow includes data cleaning, feature extraction, and model training to classify SMS messages as spam or non-spam.

Dataset: 

    The project utilizes an SMS Spam Collection dataset from Kaggle, containing diverse examples of spam and non-spam messages.

Text Preprocessing:

    Tokenizes text using nltk and applies lemmatization with WordNetLemmatizer to standardize words.
    Removes English stopwords to reduce noise in the data and enhance the model's performance.
    Outputs a cleaned and processed dataset for further analysis.

Feature Extraction:

    Converts preprocessed text into numerical features using TfidfVectorizer, which computes term frequency-inverse document frequency values.

Model Training and Evaluation:

    Splits the dataset into training and test sets using train_test_split. A RandomForestClassifier is trained on the vectorized text data. The model's performance is evaluated using accuracy score and a detailed classification report.

This project highlights the integration of natural language processing (NLP) techniques and machine learning algorithms to build an effective spam detection system. It is a foundational approach suitable for expanding into more complex text classification tasks.
