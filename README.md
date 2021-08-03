Idea: To create a dataset of books using web scraping. The dataset comprises of books names, links from where it can be purchased, prices of books, number of pages, writer of the book, type of genre from which book belongs like travel, adventure, love, fiction etc. This dataset can further be extended and can integrate with machine learning to build a recommender system for the user, which can recommend books to the user based on past purchases and similar kinds of users purchases.

Website used for webscarping: https://books.toscrape.com

For creating the dataset, python is selected as language and in that for web scraping BeautifulSoup is used as a library.
Reasons for selecting BeautifulSoup are:
-> perform web scraping is speedy.
-> because it is asynchronous, there is no need to wait to make one request at a time. 
-> it can make requests parallel.

It is the requirement of authentication and authorization from the website that we want to scrape. Some websites follow HTTP basic authentication, some require OAuth through API(Application Programming Interface). The website used in the project follows HTTP basic authentication.

Now after authentication we are ready to scrape. Beautiful soup scrapes data on the website ad provides output in html format. From given html code, its time to fetch out useful information for project like book name, its prices, number of pages, author of the book, category under which book is present. Now all the fetched can be stored in csv file.


