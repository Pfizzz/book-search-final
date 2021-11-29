# Book Search
## A (broken) app that uses GraphQL and MongoDB
![image](https://github.com/Pfizzz/book-search-final/blob/855a947851bed66cdf3752c4e04c508e58c8b14f/images/ss1.png)

This project was an attempt to replace a RESTful API framework with GraphQl, with mixed results.

## What works:
* Apollo has been successfully integrated into the back-end.
* Back-end typeDefs are finished, some resolvers have full-functionality
* Authentication is fully-functional
* addUser creates a new user with a hashed password, and returns a JSON web token
* login successfully logs in a created user, and returns a unique JWT that changes after each login

![image](https://github.com/Pfizzz/book-search-final/blob/855a947851bed66cdf3752c4e04c508e58c8b14f/images/addUser.png)
addUser functioning as expected
![image](https://github.com/Pfizzz/book-search-final/blob/855a947851bed66cdf3752c4e04c508e58c8b14f/images/login.png)

login returning unique JWT

## What doesn't
* me query returns "null"
* remaining resolvers cannot be completed
* cannot sync with front-end
* cannot deploy to Heroku for an unkown reason
![image](https://github.com/Pfizzz/book-search-final/blob/855a947851bed66cdf3752c4e04c508e58c8b14f/images/ss2.png)

Cropped photo of connection config var acquired from mongoDB and added to Heroku settings
