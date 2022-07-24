# Music-Meta-Brain

It is implemented in Python, scraped around 4500 Wikipedia articles about Indian musicians, songs and their albums using BeautifulSoup and constructed a knowledge graph in an unsupervised setting which helps to extract relevant information with context for music search queries.

wiki_sentences_v2.csv contains the text extracted from the scraped Wikipedia articles.

Extract_doc_using_BS.ipynb describes how to extract text from a Wikipedia article using BeautifulSoup.

KG_Construction_from_text.ipynb reads the text from extracted Wikipedia articles and constructs a Knowledge graph in an unsupervised setting.

This Knowledge graph is useful in determining context for search engines, user personalization, Ad targeting etc.