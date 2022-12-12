Questions
1.	What is responsible for defining the routes of the games resource?
-	Server.js with the help from create_router.js from the helpers folder

2.	What do you notice about the folder structure? Whats the client responsible for?
-  client is responsible for making requests to the server to be able to show data from db on web as well as create / edit / delete instances of data


3.	Whats the server responsible for?
- server creates routes, passes on requests from client to db, getting what’s requested and passing on to the client

4.	What are the the responsibilities of server.js?
- it helps connect server to to db

5.	What are the responsibilities of the gamesRouter?
- it connects server to create_router.js in helpers folder and allows the server to use createRouter functions

6.	What process does the the client (front-end) use to communicate with the server?
- express

7.	What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
-	The second argument is an init object which allows to control a number of different settings. In this application it is used to request a http method to either add a new instance  or remove an already existing one.

8.	Which of the games API routes does the front-end application consume (i.e. make requests to)?
- baseURL

9.	What are we using the MongoDB Driver for?
- to connect to MongoDB and work with data

 
