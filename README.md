
Sample files:
The entire Inscriptions of Aphrodisias corpus can be downloaded in a single zip file from here:
http://insaph.kcl.ac.uk/iaph2007/inscriptions/xml-repo.html
A sample file is also available at that link.

To run the code:
The code and output are provided as notebooks. The notebooks should be run from the same location as the extracted inscription files. Alternatively, the results are readable on github.

To run them, the following imports will be needed:

import glob
import pandas as pd
import bs4 as bs
from bs4 import BeautifulSoup
import lxml as lx
from bs4 import NavigableString

import greek_accentuation.characters as gachar
import greek_accentuation.syllabify as gasyb
import math
import nltk
from nltk.tokenize.regexp import WhitespaceTokenizer
import matplotlib.pyplot as plt
import scipy.stats as sp
from sklearn.naive_bayes import MultinomialNB
from sklearn.feature_extraction.text import TfidfTransformer

The first notebook to run needs to be epidoc_to_csv. Either of the others can be run after that.
