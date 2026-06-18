# Hassaniya Dialect — Sentiment Analysis

Fine-tuning of MARBERTv2 for sentiment classification
of the Hassaniya dialect (Mauritania).

## Results

| Model | Accuracy | F1-Score |
|-------|----------|----------|
| MARBERTv2 + Data Augmentation | **97.16%** | **> 0.96** |

## Dataset

- 1 851 original phrases → 7 404 after augmentation ×4
- 3 classes : Positive / Neutral / Negative
- Source: Mendeley Data — Université de Nouakchott

## Method

- Preprocessing + 62 Hassaniya stopwords
- Data Augmentation ×4 (deletion, swap, insertion)
- Fine-tuning MARBERTv2 (10 epochs + Early Stopping)
- Class weights to balance Neutral class
- Interactive demo with Gradio (Accuracy: 97.16%)

## Files

| File | Description |
|------|-------------|
| `Hassaniya_Sentiment_Analysis_Final.ipynb` | Main notebook |
| `projectHA_DATASET_-_VF.csv` | Hassaniya dataset (1 851 phrases) |
| `H-Stopwords.txt` | Hassaniya stopwords list (62 words) |

## Author

**Moustapha Yahdih**
Master 1 Artificial Intelligence — NLP & Computer Vision
Université de Nouakchott — 2025/2026
