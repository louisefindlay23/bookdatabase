# Book Database

## About Book Database

Book Database is a small Node.js web app I created as an example for my [Getting to Grips with Databases: Developing Your First Data-Driven Node.js Web App tutorial](https://www.section.io/engineering-education/working-with-databases-part2).

It teaches developers (who have never worked with databases before) how to add, modify and delete entries in a MongoDB collection (stored in a local MongoDB database) using a front-end form in a Node.js web app. 

I also used it as an opportunity to learn the updated syntax for the MongoDB Node.js module as previously I'd only used a 2.0 version.

Continuing the book example in [Part 1](https://louisefindlay.com/blog/getting-to-grips-with-databases-part1), the web app displays three forms: add, delete and modify. Users can type in a book's name and/or genre and then view a table of the updated database entries. CSS from [CSSTricks](https://css-tricks.com/complete-guide-table-element) is used to nicely style the table and I used Flexbox and CSS Variables for the layout and colours.

## Installing Book Database

Want to take a look at Book Database? Clone the repo using `git clone https://github.com/louisefindlay23/bookdatabase` and then run `npm install` in the terminal. Once all the required modules have been installed, create a local MongoDB database and and collection. Update `server.js` accordingly to the name of your database and collection. Finally, run `npm start` and go to `localhost:8080` in your browser.

Need a helping hand? Check out [Part 1](https://louisefindlay.com/blog/getting-to-grips-with-databases-part1) and my guide to [getting started with Node.js](https://louisefindlay.com/blog/static-site-to-nodejs-web-app).