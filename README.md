# Sentiment_analysis

I collect data using google-play-scraper. Take most recent comments from the most popular apps on Google Play:
Filto Video Editor, Musically, Cash App, ScoreCenter Live: All sports and Daily Diary: Journal with Lock. All comments have a text and rating from 1 to 5 stars, witch I change to 0 >> negative,  1 >> neutral, 2 >> positive.  <p>
- In the first, long work I use BertTokenizer and pretrained BertModel from Hugging Face and add Dropout and Linear layers to be able train classifier. 
- In the second, short work I use AutoModelForSequenceClassification and AutoTokenizer where choose pretrained BERT weights and train using Hugging Face builted function. 

I did only 3 epoches in each work and, obviously, BertTokenizer and BertModel work better. 
