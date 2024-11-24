# Twitter Scrap and Sentiment Analysis 🚀
This repository provides a comprehensive pipeline for scraping Twitter data and performing sentiment analysis, with a focus on topics related to COVID-19 in Indonesia. It combines a lexicon-based approach and machine learning models, including pretrained Indonesian NLP models like IndoBERT Lite.

## Key Features:
- Twitter Data Collection: Scrapes tweets related to specified keywords and hashtags.
- Sentiment Analysis:
- Lexicon-Based: Utilizes predefined sentiment lexicons tailored for the Indonesian language.
- Machine Learning-Based: Incorporates pretrained models such as IndoBERT Lite Base for enhanced sentiment classification.
- Data Preprocessing: Includes text cleaning (removal of URLs, mentions, and hashtags), tokenization, and stemming optimized for Indonesian texts.
- Visualization: Generates insightful visualizations of sentiment trends over time.

## Tech Stack:
- Python
- Hugging Face Transformers for leveraging IndoBERT
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for data visualization
- Beautifulsoup and Selenium

## Applications:
- Analyzing public sentiment trends on various topics.
- Monitoring social media discussions around health crises like COVID-19.
- Conducting research on sentiment analysis in low-resource languages.

## Prerequisites:
- Python environment with the required dependencies installed.

## Installation:
- Clone this repository.
- Install dependencies using pip install -r requirements.txt.
- Set up your Twitter API credentials in the configuration file.

## Contributions:
Feel free to contribute by submitting issues, improving the pipeline, or adding new features.
