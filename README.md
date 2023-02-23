# Social Network Api

## Table of Contents
1. [Title](#title)
2. [Project](#project)
3. [Description](#description)
4. [Installation](#installation)
5. [Usage](#usage)
6. [User Story](#user-story)
7. [Acceptance Criteria](#acceptance-criteria)
8. [Video Preview of Project](#video-preview-of-project)
9. [Source](#source)

## Title :
### Social Network Api

## Project :
### *Social Network Api*

## Description :
* This project uses use Express.js for routing, a MongoDB database, and the Mongoose ODM.
* This project is an API for a social network web application where users can share their thoughts, react to friends' thoughts, and create a friend list. 

## Installation :
The user needs to install Node.js, npm dependencies, and MongoDB.

## Usage :
- In the root directory terminal, install the npm dependencies with `npm i`.
- Then to start the server, type `npm start`.
- Insomnia was used to test the api routes and endpoints. 

## User Story :
```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria :
```md
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


## Video Preview of Project :
[Video Preview](https://drive.google.com/file/d/16l42jtC1QgpY9Xu6NxL-oFk2uBXm0qbR/view)

## Source :
- GitHub Link: https://github.com/jeremy-fong/social-network-api
