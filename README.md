# Hotel-Ratings-Prediction-Through-Sentiment-Analysis

## Objective
This project utilizes sentiment analysis to analyze various hotel reviews from  Tripadvisor, and predict corresponding ratings of five levels. The resulted models in this project could potentially be applied to small hotel booking sites which do not provide ratings of accommodation experience.

## Approaches
### Baseline: Multinomial Naive Bayes Classifier 
- Two assumptions:
    - The text document is represented as a bag of words so that word positions are not considered
    - Conditional probabilities of occurrences of words given a class are assumed independent 
- Calculate Posterior probabilities in log space

### Deep RNN: Bidirectional LSTM Network
![image](https://user-images.githubusercontent.com/49551916/111390458-238cbe80-8689-11eb-929f-fe1412051c50.png)


## Data
A hotel review dataset crawled from Tripadvisor which consists of 20,491 reviews in text along with corresponding quantitative ratings.
- Data cleansing
- Word embedding

