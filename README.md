### Diction & dictionary scrapping.

The task is to write an application which, when given a web page will download the text on it and output a sorted list of the unique words on the page, with counts of the occurrences.


We first create a web crawler or scraper with the help of the requests module and a beautiful soup module, which will extract data from a given web pages and store them in a list.

Undesired words or symbols like special symbols, blank spaces will be filtered in order to ease the counts.

## Modules

<p>**requests** : Will allow you to send HTTP/1.1 requests and many more.</p>
<p>**beautifulsoup4** : Used for parsing HTML/XML to extract data out of HTML and XML files.</p>
<p>**operator** : Exports a set of efficient functions corresponding to the intrinsic operators. </p>
<p>**collections** : Implements high-performance container datatypes.</p>

## Scraping Rules
1. You should check a website’s Terms and Conditions before you scrape it. Be careful to read the statements about legal use of data. Usually, the data you scrape should not be used for commercial purposes.
2. Do not request data from the website too aggressively with your program (also known as spamming), as this may break the website. Make sure your program behaves in a reasonable manner (i.e. acts like a human). One request for one webpage per second is good practice.
3. The layout of a website may change from time to time, so make sure to revisit the site and rewrite your code as needed
