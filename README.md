# 🎭 Sentiment Analysis with HuggingFace

Sentiment classification on 500 IMDB movie reviews using a pre-trained DistilBERT model — no training, just inference and analysis.

## The interesting part

Not the code (it's short) — it's what the model gets *wrong*. The error analysis section shows which reviews confused the model and why: sarcasm, mixed opinions, and ambiguous language are where it breaks down.

## Results

- ~93% accuracy on 500 IMDB reviews
- Confusion matrix + confidence distribution included
- 8 failure cases analyzed with review snippets

## Run it

```bash
pip install -r requirements.txt
jupyter notebook notebooks/sentiment_analysis.ipynb
```

Or open directly in Google Colab.

## What I learned

Pre-trained models are powerful out of the box, but understanding *where* they fail is what separates using a tool from understanding it.