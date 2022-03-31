# Micro Service

# The project - Dashboard

The purpose of this project is to implement a web application that works like Netvibes.
The user will first connect to our application and then subscribe to different services that are accessible from our solution.
Each of these services would offer different widgets

...

First of all to run our app you have to install all dependecies.
Inside front-end and back-end directories, run:

```
npm i
```

Make sure you have your SQL DB running in port 3306, and just change the credentials in the index.js from the backend folder. The DB's instructions are in `db.sql` inside of back-end folder.

When everything is set up, just run the application

```
nodemon
```

To start the back, and

```
npm start
```

to run the front.

Then access the site on your [browser](http://localhost:3001)

Once you arrive, you have to register yourself in order to use our modules.
Then, log yourself and go to the modules tab.

Inside, you'll see we have a lot of modules :

- Weather, which display the weather of wathever city you want 
- Dictionnary, which let you check the definiton of any word 
- News, provides you with the last 10 news availables on The Guardian
- Movies, which help you see all movies available in the world, with their overview and rates
- Tracker, this one displays the value of all crypto-currencies in the world
- Recipes : You are hungry ? Find yourself a good recipe for tonights and
- Joke : Just a random joke to make you laugh 
- Calendar : This one displays the current date, and you can choose whatever date you want to see events related to this tables.
- Sport : Find the sport you want to practice thanks to this tool.
- Gmail : this one lets you see the last mail you received in Gmail.

This application was created by Leonardo, Jules, Jonathan, Remi and Olivier.

Thanks.


