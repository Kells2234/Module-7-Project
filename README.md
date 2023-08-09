# Project Title

Module 7 Final Project: Web Scraping

## Student Name
Kelly Simmons

## Description
This project is part of the Web Mining and Applied NLP (44-620) course. The purpose of this file is to scrape important information from an Forex Trading artical then creating visuals using spaCy.URL for the artical is https://admiralmarkets.com/education/articles/forex-basics/forex-day-trading-explained. 

## Table of contents

### Scrape article to get data
Read in code that will scrape the the artical for data.

### Read in data scrapped from article
The code in this section attempts to access the CSV file and reads it into my repo creating a new file named Forex Pair Data.

### Data processing with Spacy module
Read in data into Spacy creating visuals

## Installation

To use this project, make sure you have Python 3.8 installed on your system. Do not install modules like math and statistics. You can check your Python version by running the following command in your terminal:

```shell
python --version
```

### Modules

The following modules are required for the installation of this project:
<br>
```
import json,pickle,requests,spacy,re,nltk
from spacytextblob.spacytextblob import SpacyTextBlob
from spacy.lang.en.stop_words import STOP_WORDS
import matplotlib.pyplot as plt
from collections import Counter
from sumy.parsers.html import HtmlParser
from sumy.nlp.tokenizers import Tokenizer
from sumy.summarizers.lex_rank import LexRankSummarizer
from nltk.tokenize import sent_tokenize
import numpy as np
nltk.download('punkt')
```

## Resources used

- ChatGPT by OpenAI
- Kaggle
- Previous Modules from this course
