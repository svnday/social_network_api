# Social_network_api
This app is for the Module 18 challenge in my Full Stack Web Developer bootcamp. This is a node.js application that serves as a back-end for a social network that uses MongoDB as the database.

Through the command line, an admin is able to create users, add "thoughts" assigned to those users like posts, link users as friends, and add users' reactions to thoughts. Users, thoughts, and reactions can all be deleted as well.

## User Story

```
AS A social media startup  
I WANT an API for my social network that uses a NoSQL database  
SO THAT my website can handle large amounts of unstructured data  
```

## Acceptance Criteria

```
GIVEN a social network API  
WHEN I enter the command to invoke the application  
THEN my server is started and the Mongoose models are synced to the MongoDB database  
WHEN I open API GET routes in Insomnia for users and thoughts  
THEN the data for each of these routes is displayed in a formatted JSON  
WHEN I test API POST, PUT, and DELETE routes in Insomnia  
THEN I am able to successfully create, update, and delete users and thoughts in my database  
WHEN I test API POST and DELETE routes in Insomnia  
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list  


```

## Technology Used
```
This project uses the following technologies:  
Javascript  
Node.js  
MongoDB  
Mongoose  
Express  
```

## Instructions For Use
```
First, `git clone` the repository down to your local machine.  
Next, install dependencies by running `npm init`
Start the server by running command `npm start`

To test the application, open a program such as Insomnia and test the routes.
```

____________________________________________________________________________________________________


Link to repository: [https://github.com/svnday/social_network_api](https://github.com/svnday/social_network_api)  
[Link to demo video](https://streamable.com/d2ur7h)
