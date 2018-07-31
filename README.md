# dinoScour
Scour the most popular opportunities in the coding world! A great resource for developers of all skill levels.
Click the Titles to leave yourself a note. Click the Links for more detailed information.


## How it Works:

Users can visit the domain/scrape path to scrape the craigslist website for the most up to date opportunities in the coding world. Then after the scrape is completed, can go back to the homepage to see the most recent list. Added functionality includes being able to click on the title of the article, leaving notes for each specific article, and also being able to click on the link for more information on the particular subject.  


## Running the app locally:

1.  Start by installing all of the npm dependencies:
    - axios
    - body-parser
    - cheerio
    - express
    - express-handlebars
    - mongoose
    - morgan
    - request
2. Next run the server.js file to start the server. This will automatically set up your Mongo db as well.
3. Open up the browser and navigate to localhost:3000.
4. If everything is working properly you should see the homepage.
5. Next, visit the URL localhost:3000/scrape. This will call the scrape function and update the articles.
6. Navigate back to localhost:3000 to see the updated articles. 
7. Click on the title of the app to leave notes associated with that particular article. 
8. You can also click on the link underneath the title and be directed to more detailed information in a new tab.


## Deployment:

https://protected-atoll-18488.herokuapp.com/


## Built With:
```
HTML,
CSS,
Bootstrap,
Javascript,
JQuery,
Node.js,
Node Express,
NPM,
MongoDB,
Heroku,
Mongoose
```
