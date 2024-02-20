<br>
  <h1 align="center">Tech Blog using Model-View-Controller (MVC)</h1>

![Badge](https://img.shields.io/badge/License-MIT-yellow.svg) ![JavaScript](https://img.shields.io/badge/JavaScript-red) ![Node.js](https://img.shields.io/badge/Node.js-blue) ![Express.js@4.18.2](https://img.shields.io/badge/Express.js@4.18.2-lightgreen) ![Express Session@3.1.0](https://img.shields.io/badge/ExpressSession@3.1.0-pink) ![Express Handlebars@1.18.0](https://img.shields.io/badge/ExpressHandlebars@1.18.0-yellow) ![MySQL2@3.9.1](https://img.shields.io/badge/MySQL2@3.9.1-purple) ![Sequelize@6.37.1](https://img.shields.io/badge/Sequelize@6.37.1-lightblue) ![ConnectSessionSequelize@7.1.7](https://img.shields.io/badge/ConnectSessionSequelize@7.1.7-lavender) ![Bcrypt@5.1.1](https://img.shields.io/badge/Bcrypt@5.1.1-red) ![Dotenv@16.4.4](https://img.shields.io/badge/Dotenv@16.4.4-blue)

## Description
"Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies. A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!

Your challenge this week is to build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. You’ll build this site completely from scratch and deploy it to Heroku. Your app will follow the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication."


#### This application, upon setup and execution, facilitates the following functionalities:

<br>

### Brief functionality walk through:
![Mock-Up](./assets/mockup.gif)


## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Technologies Used
- JavaScript
- Node.js
- Express.js (4.18.2)
- Express Session (1.18.0)
- Handlebars (4.7.3)?
- Express Handlebars (3.1.0)
- MySQL2 (3.9.1)
- Sequelize (6.37.1)
- Connect Session Sequelize (7.1.7)
- Bcrypt (5.1.1)
- Dotenv (16.4.4)

## Installation

  `npm init -y`: create a package.json file
  <br>
  `npm install`: install dependencies

### Dependencies
  `npm i express`: back end web application framework to build the RESTful APIs
  <br>
  `npm i express-session`: middleware module in Express. js that allows you to create sessions in your web application
  <br>
  `npm i express-handlebars`: logicless templating languages that renders web pages to the client side from data on the server side
  <br>
  `npm i mysql2`: database management system
  <br>
  `npm i sequelize`: node.js-based Object Relational Mapper, that simplifies interacting with SQL
  <br>
  `npm i connect-session-sequelize`: add authentication
  <br>
  `npm i bcrypt`: a library to hash passwords
  <br>
  `npm i dotenv`: protection of sensitive information

## User Story

```md
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Acceptance Criteria

```md
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts
```

## Usage
Run this application with the command:

## License

The application is covered under the following license: [MIT](https://opensource.org/licenses/MIT)

## Contributing

I will not be accepting contributions to this repository at this time.
<br>

## Questions

Questions about this repository? My best point of contact is via [Email](mailto:jayastarrbaldwin@gmail.com)
<br>
If you'd like to view more of my work in GitHub, my profile is: [jayabaldwin](https://github.com/jayabaldwin)