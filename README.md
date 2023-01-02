# Web-Scrapping-for-CFC

In this repository we create a web scrapping code that finds all external resources of the cfc official webpage. Then we will create a word counter for the privacy policy section. Both outputs will be writen in relative JSON files.


This code first retrieves the index webpage and then uses BeautifulSoup to parse the HTML. It then looks for all tags that have a src or href attribute, and adds any external URLs to a set. It then writes this set to a JSON file.

Next, the code searches the page for a hyperlink with the text "Privacy Policy" and gets the URL of this page. It then retrieves the privacy policy page and uses BeautifulSoup to parse the HTML. It then creates a case-insensitive word frequency count and writes this to a JSON file.
