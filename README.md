# Scrape
** version 1.0.0

A brief description of the project

It's no secret Hacker News is one the most goto websites in the tech community
In this project I am making the Hacker News much more efficient to use by scraping it with a simple program,Scrape.

Scrape is designed specifically to scrape Hacker News(https://news.ycombinator.com/news) 
## Functions

- When scrape is executed it pulls and displays stories from Hacker News that have a minimum of 100 votes and ignores all the rest.
This will save time scrolling through all the stories.

-  After pulling the stories with 99+ votes, scrape reorders them from the highest vote to least  to for users to start with the top stories.
-  The program is scrapping only from the first 2 pages of Hacker News for now
-   Hacker News is dynamically updated, therefore, stories that previously did not make it to the list could eventually be displayed if they gained 99+ votes

## Python libraries Used
- Requests
- BeautifulSoup
- PPTINT
 

## Try it
 
 1 - Please save or download the project file 
 2 - Open it in your terminal
 3 - run: python3 scrape.py

## Upcoming Features
- Increase the number of pages to scrapes from Hacker News
- Users will have the possibility to display the important stories with only one click.
-  User will be able to set some preferences about the type of stories they really want to see
-  I will be expanding scrape to the top 5-10 websites in the tech industry and users will have the option to choose 1 source at the time.
- An API to make it a quick on the go app that scrapes the top 10 popular tech websites so and easy to be integrated

## Contributors:
None for now
