### Diction & dictionary scrapping.

The task is to write an application which, when given a web page will download the text on it and output a sorted list of the unique words on the page, with counts of the occurrences.


We first create a web crawler or scraper with the help of the requests module and a beautiful soup module, which will extract data from a given web pages and store them in a list.

Undesired words or symbols like special symbols, blank spaces will be filtered in order to ease the counts.
