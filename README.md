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
     ![sentiment counts](https://user-images.githubusercontent.com/67052212/228441755-0a6fea86-f9eb-472b-89ec-d6c377834c3b.png)

      
<li> Wordclouds analysed for product names and summary of review features.
     ![product name wordcloud](https://user-images.githubusercontent.com/67052212/228441795-80ec2b8e-dc2d-4955-8e29-98ff66f09f14.png)
      
     ![summary wordcloud](https://user-images.githubusercontent.com/67052212/228441823-a37aa076-df8b-46e3-95a8-acea3683facb.png)
      
      
<li> DistilBERT model fine-tuned on the data
     Recall: 0.94 Precision: 0.94
     Note: Negation are also identified in the input string
     E.g "I am not unhappy with this product." -> Sentiment: Positive 
     
<li> Topic Modelling performed for product names and summary of review features. Topics visualized in a 2D space for inter-topic distance
     ![product_name_topic_modelling](https://user-images.githubusercontent.com/67052212/228441855-5fb256d5-2d40-43d6-958d-e2732d1cddb7.png)
      
<\ul>

