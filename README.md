# Lab 10
Connect a database to your api

## Let's create a simple bit.ly API
Today will be an experiment in what's called pair programing: where you the class and myself will pair program to build a simple API for bit.ly. I will post the code we come up with in the class examples folder

## Prep Work
Please run the following commands to install the newest version of NodeJS to your computer and install sqlite:

 1. sudo npm install -g n
 2. sudo n stable
 3. cd into your root directory
 4. npm install express --save
 5. npm install sqlite3 --save

## In class: set up environment, create the table, and select/insert new entries to the table
We will build an api with two endpoints that does the following:

 1. Add a new link to our database
 2. Return all of the links created
 
## On your own: after the above, create a third endpoint that returns the long url
 - The input is the short url
 - The output is the long url
