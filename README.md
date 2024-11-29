
# Propaganda Detection and Classification in Tweets

This Repo evaluates various Natural Language Processing (NLP) techniques for detecting and classifying propaganda in tweets. The study explores approaches ranging from traditional Machine Learning algorithms to neural network-based and transformer-based models, comparing their performance on binary and multiclass classification tasks.


The Repo analyzes models like CNN-LSTM, Bidirectional LSTM, and Transformer-based models (e.g., BERT) to classify tweets into propagandistic and non-propagandistic categories. It also investigates the impact of different word embeddings, such as TF-IDF and Word2Vec, achieving up to **90% accuracy for binary classification** using BERT.

## Key Features
- **Machine Learning Models**: Logistic Regression, K-Nearest Neighbors, Random Forest, Linear SVC, SGD Classifier, and Nearest Centroid.
- **Neural Network Models**: CNN-LSTM and Bidirectional LSTM.
- **Transformer-Based Models**: BERT for binary and multiclass classification tasks.
- **Preprocessing**: Tokenization, removal of punctuations, stopwords, and numerical characters, along with analysis of bigrams and trigrams.

## Dataset
The dataset consists of labeled sentences in nine categories:
- **Propaganda Types**: Flag-waving, appeal to fear/prejudice, causal simplification, etc.
- **Non-Propaganda**: Tweets labeled as not containing propaganda.

## Results
- **BERT**: Achieved up to 90% accuracy in binary classification and 45% accuracy for eight-class classification.
- **CNN-LSTM**: Effective for capturing spatial and temporal features in text but less accurate compared to BERT.
- **BiLSTM**: Demonstrated better handling of multiclass classification than CNN-LSTM.

### Performance Highlights
- **Machine Learning Models**: Random Forest outperformed other traditional models with the highest F1-score.
- **Transformer Models**: BERT surpassed both CNN-LSTM and BiLSTM due to its ability to capture long-range dependencies and its pre-training on large datasets.

Transformers like BERT are highly effective in detecting and classifying propaganda in tweets, outperforming traditional and neural network-based methods. Future work involves expanding the dataset using Twitter APIs to enhance model performance further.



## Future Work
- Expanding the dataset via Twitter API for better generalization.
- Exploring additional NLP techniques and feature engineering strategies.
