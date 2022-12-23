# sentiment-analysis
Sentiment analysis task on the Amazon jewelry reviews dataset

## basic-models.ipynb
- Data cleaning on the dataset
    - Convert all reviews into lowercase
    - Remove HTML/URL content from reviews
    - Remove non-alphabetic characters
    - Remove extra spaces
    - Perform contractions on the reviews
- Preprocessing steps
    - Stop word removal
    - Lemmatization
- Feature extraction using TF-IDF
- Train models such as
    - Single Layer Perceptron
    - Support Vector Machine
    - Logistic Regression
    - Multinomial Naive Bayes

## advanced-models.ipynb
- Data cleaning on the dataset
    - Convert all reviews into lowercase
    - Remove HTML/URL content from reviews
    - Remove non-alphabetic characters
    - Remove extra spaces
- No preprocessing steps such as stop word removal or lemmatization
- Generate features using Word2Vec
    - Performed comparison between pretrained 'word2vec-google-news-300' model and training a Word2Vec model from scratch.
- Utilize these features and train models such as
    - Single Layer Perceptron
    - Support Vector Machine
    - Feed forward neural networks
    - Recurrent neural networks
        - Simple RNN
        - RNN with GRU
 