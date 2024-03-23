# HTML-Text-Processing-and-Unique-Word-Extraction
This Python script extracts text content from an HTML page, processes it, and extracts unique words from the processed text. The script utilizes various text processing techniques including cleaning, normalization, tokenization, lemmatization or stemming, and stop words removal.

# Data Extraction:

The script fetches HTML content from any given URL, allowing flexibility to use URLs from sources like Wikipedia or any other web page containing relevant text data.
Using Python libraries like requests and BeautifulSoup, the script extracts text from HTML elements such as paragraphs or headings etc.

# Processing Steps:

Cleaning Data: Eliminates any symbols or characters that are not relevant to the text content.
Normalization: Converts all text to lowercase to ensure uniformity for subsequent processing steps.
Tokenization: Splits the text into individual words or tokens, facilitating further analysis.
Lemmatization or Stemming: Reduces words to their base or root form to standardize variations of the same word. Users can choose between lemmatization or stemming based on their preference or requirements.
Stop Words Removal: Filters out common words such as "is," "and," "the," etc., which do not add significant meaning to the text.
Unique Word Extraction:
After processing, the script outputs all unique words present in the text data. This ensures that only distinct words are considered for analysis, providing valuable insights into the vocabulary used in the text.
