# Project Title

Module 7 Final Project: Web Scraping

## Student Name
Kelly Simmons

## Description
This project is part of the Web Mining and Applied NLP (44-620) course. The purpose of this file is to retrieve Forex Trading data from a CVS data file saved to my local computer downloded from https://www.kaggle.com/datasets/diqiland/major-forex in an effort to use Spacy to creat visuals that will nopt only show the data from the CSV file but also show current currency pair price data and update it at a specified time. Thus allowing me to see trends I can use to make good Forev Tradeing decisions.

## Table of contents

### Read in data from CSV file
The code in this section attempts to access the CSV file and reads it into my repo creating a new file named Forex Pair Data.

### Data processing with Spacy module
Read in data into Spacy creating an interactive app I can use.

### Create code to allow Spacy to update new data
Read in new codes that will allow Spacy to update data and chart it for me to see all data or just one specific currency pair price data.

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
