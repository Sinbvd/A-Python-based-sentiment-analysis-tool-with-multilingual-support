# A-Python-based-sentiment-analysis-tool-with-multilingual-support

A sentiment analysis project using Python and NLTK.

## Overview
This repository contains a Python-based sentiment analysis tool designed to handle multilingual text data. It analyzes the sentiment polarity and extracts keywords from input phrases.

## Features
- Multilingual support (French, German, Japanese, English, etc.)
- Sentiment polarity and subjectivity analysis
- Keyword extraction using NLTK
- Easy integration with Google Colab and Jupyter Notebook

## How to Use
1. Clone the repository or download the `.ipynb` file.
2. Open the file in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Follow the steps in the notebook to analyze your text data.

## Technologies Used
- Python
- NLTK
- TextBlob
- Googletrans

## Example Output
| Phrase                                              | Polarity | Subjectivity | Keywords               |
|-----------------------------------------------------|----------|--------------|------------------------|
| J'adore apprendre le Python.                       | 0.5      | 0.6          | Python                |
| Artificial intelligence is amazing and revolutionary | 0.8      | 0.95         | intelligence, revolution |

## Installation
To install required dependencies, use the following command:
```bash
pip install -r requirements.txt
