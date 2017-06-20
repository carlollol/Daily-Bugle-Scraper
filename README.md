# Homework-Daily-Bugle-Scraper

## Live Link 
- https://dailybuglescraper.herokuapp.com/

## Description
- Press the scrape article button and you'll get articles from Reddit. You can also choose to save articles and add notes to saved articles. These notes can also be deleted.

## Requirements
- Use cheerio.js to scrape from a website and display the information to the user when prompted.
- Use mongoose.js to communicated with the MongoDB to store saved artilces and notes.

## Technologies Used:
- express
- express-handlebars
- mongoose
- body-parser
- cheerio
- request

## Code Explaination
- We used cheerio to scrape the data on the selected site.
- We then use mongoose to store it on our database which we can then access and display on our application.
- You can add notes on the selected articles and save it for later view
