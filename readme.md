## Disaster Tweet Classification

Built a robust classifier using the Kaggle competition [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) dataset:

1. **Data Preparation & EDA**

   - Cleaned and normalized 10,000+ tweets (tokenization, stop-word removal, lemmatization)
   - Analyzed tweet-length distributions and keyword frequencies to inform model design

2. **Convolutional Neural Network (CNN)**

   - Applied convolutional filters over word embeddings to capture local text patterns
   - Achieved an **F1-score of 0.7934**

3. **BERT Fine-Tuning**

   - Fine-tuned a pretrained transformer for disaster-domain context understanding
   - Achieved an **F1-score of 0.8213**

4. **Ensemble Modeling**
   - Merged CNN and BERT predictions to leverage complementary strengths
   - Boosted performance to an **F1-score of 0.8247**, earning a top-139 public leaderboard rank

This end-to-end NLP pipeline—from data preprocessing through advanced deep-learning and ensembling—demonstrates expertise in text analytics and real-time classification.
