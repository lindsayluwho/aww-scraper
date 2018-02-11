# Aww Scraper

Aww Scraper is a MongoDB-based scraper for Reddit's adorable /r/aww subreddit. 

See live: [Heroku Deployment](boiling-fjord-31935.herokuapp.com)


## Database

Aww Scraper's database is composed of MongooseJS models, Article and Note. Article stores the titles and links to each post scraped. Note stores comments added by Aww Scraper's users associated with individual articles. 

## Scraping

Scraping is completed by the Request NodeJS package and handled with the Cheerio NodeJS package. 

## DOM Manipulation

jQuery is used to make AJAX calls to the server and display article data stored in the database. 

