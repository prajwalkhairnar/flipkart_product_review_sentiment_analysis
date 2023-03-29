# Flipkart Product Reviews

## Sentiment Analysis
## Topic Modelling

Data : Kaggle

      https://www.kaggle.com/datasets/niraliivaghani/flipkart-product-customer-reviews-dataset
      
      
<ul>
<li>This analysis consists of Exploratory Data Analysis for free text data from the Flipkart Product Reviews dataset. 
<li>Sentiment analysis was performed using DistilBERT model from huggingface by fine-tuning it for the product reviews data. 
<li>Topic modelling was performed using BERTopic with a spacy model for embeddings. 
<\ul>


------------------------------------------------------------------------------


## Highlights

<ul>
<li> The counts for sentiments (Positive, Negative, Neutral) are analysed as per the price range of products. 
![sentiment counts](https://github.com/prajwalkhairnar/flipkart_product_review_sentiment_analysis/blob/main/plots_figures/sentiment%20counts.png)

<li> Wordclouds analysed for product names and summary of review features.
![product name wordcloud](https://github.com/prajwalkhairnar/flipkart_product_review_sentiment_analysis/blob/main/plots_figures/product%20name%20wordcloud.png)

![summary wordcloud](https://github.com/prajwalkhairnar/flipkart_product_review_sentiment_analysis/blob/main/plots_figures/summary%20wordcloud.png)

<li> DistilBERT model fine-tuned on the data
     Recall: 0.94 Precision: 0.94
     Note: Negation are also identified in the input string
     E.g "I am not unhappy with this product." -> Sentiment: Positive 
     
<li> Topic Modelling performed for product names and summary of review features. Topics visualized in a 2D space for inter-topic distance
![product name topic modelling](https://github.com/prajwalkhairnar/flipkart_product_review_sentiment_analysis/blob/main/plots_figures/product_name_topic_modelling.png)
<\ul>

