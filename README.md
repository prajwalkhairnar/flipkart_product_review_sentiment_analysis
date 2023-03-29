# Flipkart Product Reviews

## Sentiment Analysis | Topic Modelling 

Data : Kaggle

      https://www.kaggle.com/datasets/niraliivaghani/flipkart-product-customer-reviews-dataset
      
      
<ul>
<li>This analysis consists of Exploratory Data Analysis for free text data from the Flipkart Product Reviews dataset. 
<li>Sentiment analysis was performed using DistilBERT model from huggingface by fine-tuning it for the product reviews data. 
<li>Topic modelling was performed using BERTopic with a spacy model for embeddings. 
<\ul>


------------------------------------------------------------------------------
<br>
<br>

## Highlights

<ul>
<li> The counts for sentiments (Positive, Negative, Neutral) are analysed as per the price range of products. 

<img
  src="plots_figures/sentiment counts.png"
  alt="Sentiment Counts"
  title="Sentiment Counts"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
      
<li> Wordclouds analysed for product names and summary of review features.

      
<img
  src="plots_figures/product name wordcloud.png"
  alt="Product Name Wordcloud"
  title="Product Name Wordcloud"
  style="display: inline-block; margin: 0 auto; max-width: 50px">
      
<img
  src="plots_figures/summary wordcloud.png"
  alt="Summary Wordcloud"
  title="Summary Name Wordcloud"
  style="display: inline-block; margin: 0 auto; max-width: 50px">
      
<br>      
<br>
      
<li> DistilBERT model fine-tuned on the data <br>
     Recall: 0.94 Precision: 0.94 <br>
     Note: Negation are also identified in the input string
     > E.g "I am not unhappy with this product." -> Sentiment: Positive 
     
<li> Topic Modelling performed for product names and summary of review features. Topics visualized in a 2D space for inter-topic distance

<img
  src="plots_figures/product_name_topic_modelling.png"
  alt="Product Name Topic Modelling"
  title="Product Name Topic Modelling"
  style="display: inline-block; margin: 0 auto; max-width: 50px">

