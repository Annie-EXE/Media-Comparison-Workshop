# About

The files in this repository extract and process data from news articles.

## Setup and Installation

- It is recommended to create a venv
- `pip install -r requirements.txt`
- `python setup_nltk.py`

## Environment

Add a `.env` file which has the following keys stored:

```
FEED_URL_A=XXXXX
FEED_URL_B=XXXXX
```

Each value should be a valid RSS URL.

## Development

- Run `python extract.py` to download the initial data to a `.csv` file
- Run `text_processing.ipynb` to clean and process the data, and identify semantic keywords for each article

## Possible tasks

- Look at word frequency
- Look at sentiment of titles
- Use headlines/keywords as input to an ML model
- Topics/areas of concern
