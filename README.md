# Sentiment Analysis of Amazon Customer Reviews

## What this is
A NLP project that analyzes Amazon customer reviews and builds a binary sentiment classifier (positive / negative).  
The notebook performs data loading, basic EDA, text cleaning, tokenization, stopword removal, and model experiments.

## Files
- `NLP_project.ipynb` — main Colab notebook with the full analysis and code.  
  Open in Colab: https://github.com/daniahqaddomi/Sentiment-Analysis-of-Amazon-Customer-Reviews/blob/main/NLP_project.ipynb

## Data
The notebook reads the dataset from:
https://media.githubusercontent.com/media/juliandariomirandacalle/NLP_Notebooks/master/01-Introduction_NLP/Customer_Reviews.csv

Reviews are mapped to a binary label:
- Score > 3 → positive (1)
- Score < 3 → negative (0)

## Quick start
1. Open `NLP_project.ipynb` in Google Colab (recommended) or run locally in Jupyter.
2. Run cells from top to bottom. The notebook downloads required NLTK data at runtime.
3. Inspect results: EDA plots, word cloud, class distribution, preprocessing, and model metrics.

## Requirements
- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- nltk
- scikit-learn
- wordcloud

## Notes
- Preprocessing includes: lowercase, remove non-alphanumeric characters, tokenization, and stopword removal.
- The dataset used in the notebook contains ~10k reviews; after filtering neutral reviews there are ~9k rows for training/analysis.
