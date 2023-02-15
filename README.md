# Jukun Historian Chatbot(using NLTK)
 I believe if we teach AI our culture it will hellp us preserve it! This repo is for the Jukun Historian ChatBot. The Jukun tribe are an ethno-linguistic group or ethnic nation in West Africa. Unlike other prominent cultures like Yoruba, Hausa and Igbo, msny other tribe, yet with very rich culture heritage has not been given enough exploration. This AI Bot attempts to be a tool to help people know more about this tribe.
 
# Outline
* [Motivation](#motivation)
* [Blogpost](#blogpost)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)


## Motivation
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.This was one of my very first projects, created  when I just stepped into the world of NLP and I thought of creating a simple chatbot just to make use of my newly acquired knowledge.


## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```

## How to run
* Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK/master)

You can run the [chatbot.ipynb](https://github.com/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK/blob/master/Chatbot.ipynb) which also includes step by step instructions.
* Through Terminal
```
python chatbot.py
```
