What are the most frequent words in Herman Melville's novel Moby Dick and how often do they occur? To answer this question we first need the text of the book which is freely available online at Project Gutenberg (contains a large corpus of books) as an HTML file: https://www.gutenberg.org/files/2701/2701-h/2701-h.htm.

To fetch the HTML file with Moby Dick Python package request is used to make a GET request for the website. Then to extract words from this web data BeautifulSoup is used. and the analysis of the distribution of words is done using the Natural Language ToolKit (nltk).

So, what word turned out to be the most common word in Moby Dick?
The answer is "whale"
