# Sentiment_analysis

I collected data using google-play-scraper and took recent comments from the most popular apps on Google Play:
Filto Video Editor, Musically, Cash App, ScoreCenter Live: All sports, and Daily Diary: Journal with Lock. All comments have a text and rating from 1 to 5 stars, which I change to 0 >> negative,  1 >> neutral, 2 >> positive.  <p>
- In the first, long work,  I used BertTokenizer and pretrained BertModel from Hugging Face and added Dropout and Linear layers to be able to train classifier. 
- In the second, short work, I used AutoModelForSequenceClassification and AutoTokenizer where I chose pretrained BERT weights and trained the classifier using Hugging Face built in function. 

I did only 3 epoches in each work and, evidently, BertTokenizer and BertModel work better. 
