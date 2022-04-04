# Social Network Api
This is a network API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

![GitHub last commit](https://img.shields.io/github/last-commit/SepidehAyani/social_network_api)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/SepidehAyani/social_network_api)  ![GitHub watchers](https://img.shields.io/github/watchers/SepidehAyani/social_network_api?label=Watch&style=social)  ![GitHub top language](https://img.shields.io/github/languages/top/SepidehAyani/social_network_api)  ![GitHub license](https://img.shields.io/badge/license-MIT-blueyellow) <br> 
## User Story
As a social media startup
User wants an API for their social network that uses a NoSQL database
So that their website can handle large amounts of unstructured data.

## Table of Contents 
1. [About the Project](#About-The-Project)
1. [Project Links](#Project-Links)
1. [Demo](#Demo)
1. [Installation](#Installation)
1. [Contribution Guidelines](#Contribution-Guidelines)
1. [Project Team](#Project-Team)
1. [Questions](#Questions)
1. [License](#License)

## About The Project
Given a social network API:
- When user enters the command to invoke the application, then the server is started and the Mongoose models are synced to the MongoDB database.
- When user opens API GET routes in Insomnia or Postman for users and thoughts, the the data for each of these routes is displayed in a formatted JSON.
- When user tests API POST, PUT, and DELETE routes in Insomnia, then they are able to successfully create, update, and delete users and thoughts in the database.
- When user tests API POST and DELETE routes in Insomnia, then they are able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list.

## Project Links
[Repo Link](https://github.com/SepidehAyani/social_network_api) <br>

## Demo
![Project demo](./assets/users.gif)

## Instructions
- `git clone https://github.com/SepidehAyani/social_network_api.git`
- `npm i`
- `npm start`
- Note: Use your browser or an app like [Insomnia](https://insomnia.rest/) to test the REST API.
- Ensure that MongoDB and Express are installed on your computer.

#### Languages and libraries used in this project:
- <a href="https://nodejs.org/">Node.js</a>
- <a href="https://momentjs.com/">Moment.js</a>
- <a href="https://www.npmjs.com/package/express">Express.js</a>
- <a href="https://www.mongodb.com/">MongoDB</a>
- <a href="https://mongoosejs.com/">Mongoose</a>
- <a href="https://www.javascript.com/">JavaScript</a>

## Contribution Guidelines:
```  
Feel free to contribute to this repo by creating issues or sending an email to sepid.ayani@gmail.com
```
## Project Team
[SepidehAyani](https://github.com/SepidehAyani) <br>

## Questions
<details>
    <summary>Contact</summary>
    sepid.ayani@gmail.com
</details>

## License
#### Distributed under the MIT License. See [Choose A License](https://choosealicense.com/) for more details.