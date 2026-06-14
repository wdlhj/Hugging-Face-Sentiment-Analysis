# 🎭 Sentiment Analysis with HuggingFace

Sentiment classification on 500 IMDB movie reviews using a pre-trained DistilBERT model on HuggingFace.

## Dataset

'Stanford IMDB dataset' 50k labeled movie reviews labelled positive or negative. 
Loaded directly from HuggingFace.

## The interesting part

What the model gets *wrong*. The error analysis section shows which reviews confused the model and why sarcasm and mixed opinions are where it breaks down.

## Outcomes

- ~89% accuracy on 500 IMDB reviews
- Confusion matrix & confidence distribution included

## Run it

1. Download HF_SentimentAnalysis.ipynb raw file from the repository
2. upload the .ipynb in a google colab new notebook
3. Run the cells

## Learned that...

Understanding *where* pr-trained models fail is what separates using a tool from understanding it.
