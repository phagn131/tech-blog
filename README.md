## My Tech Blog

## User Story

As a developer who produces written content about technology, my desire is to have a blog site that functions as a content management system (CMS), enabling me to publish articles, blog posts, and share my thoughts and opinions on various topics related to technology.

## Technical and Social Reasoning

Developers not only create and debug applications, but also read and write about technical concepts, advancements, and new technologies. In this context, building a CMS-style blog site is an important task, where developers can publish their blog posts and comment on each other's posts. The site will be built from scratch, follow the MVC paradigm, and use Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.


## Technical Workflow

This is a overview of the functionality of a CMS-style blog site. When visiting the site for the first time, the homepage is presented, including existing blog posts (if any), navigation links for the homepage and dashboard, and the option to log in. Clicking on the homepage link takes the user to the homepage, and clicking on other links prompts the user to sign up or sign in. Once signed in, the user can view existing blog posts, leave comments, create and edit their own blog posts on the dashboard, and log out. If idle for too long, the user is prompted to log in again before they can add, update, or delete comments.

## Mock-Up

The following animation demonstrates the application functionality:

![Animation cycles through signing into the app, clicking on buttons, and updating blog posts.](./Assets/image/14-mvc-homework-demo-01.gif) 

### Technical Tools 

Uses the express-handlebars(https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js for your Views.

Uses MySQL2(https://www.npmjs.com/package/mysql2) and Sequelize(https://www.npmjs.com/package/sequelize) packages to connect to a MySQL database for your Models, and create an Express.js API for your Controllers.

Uses dotenv package(https://www.npmjs.com/package/dotenv) to use environment variables 
The bcrypt package(https://www.npmjs.com/package/bcrypt) to hash passwords
The express-session(https://www.npmjs.com/package/express-session) and connect-session-sequelize(https://www.npmjs.com/package/connect-session-sequelize) packages to add authentication.

## License

![license](https://img.shields.io/badge/license-MIT-blue.svg)

## 📝 Notes

- These are the (2) items required for submission
  1.  The url ling to Heroku deployment
      -ADD HEROKU LINK 
      
  2.  The URL of the GitHub repository that contains your code
      https://github.com/phagn131/tech-blog

## Contact Information:
- Github: [phagn13@github.com](https://github.com/phagn13@github.com)
- Email: [chloetechnologies@gmail.com](user@email.com)
