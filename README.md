
Sample files:
The entire Inscriptions of Aphrodisias corpus can be downloaded in a single zip file from here:
http://insaph.kcl.ac.uk/iaph2007/inscriptions/xml-repo.html
A sample file is also available at that link.

To run the code:
The code and output are provided as notebooks. The notebooks should be run from the same location as the extracted inscription files. Alternatively, the results are readable on github.

To run them, the following libraries are needed (in addition to pandas, numpy, matplotlib, scipy.stats and math):

glob,
bs4 (BeautifulSoup),
lxml,

greek-accentuation (https://github.com/jtauber/greek-accentuation),
nltk,
sklearn

The first notebook to run needs to be epidoc_to_csv. Either of the others can be run after that.
