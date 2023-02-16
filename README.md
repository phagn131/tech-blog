## My Tech Blog

## User Story

As a developer who produces written content about technology, my desire is to have a blog site that functions as a content management system (CMS), enabling me to publish articles, blog posts, and share my thoughts and opinions on various topics related to technology.

## Technical and Social Reasoning

Developers not only create and debug applications, but also read and write about technical concepts, advancements, and new technologies. In this context, building a CMS-style blog site is an important task, where developers can publish their blog posts and comment on each other's posts. The site will be built from scratch, follow the MVC paradigm, and use Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.


## Technical Workflow

This is a overview of the functionality of a CMS-style blog site. When visiting the site for the first time, the homepage is presented, including existing blog posts (if any), navigation links for the homepage and dashboard, and the option to log in. Clicking on the homepage link takes the user to the homepage, and clicking on other links prompts the user to sign up or sign in. Once signed in, the user can view existing blog posts, leave comments, create and edit their own blog posts on the dashboard, and log out. If idle for too long, the user is prompted to log in again before they can add, update, or delete comments.

## Mock-Up

The following animation demonstrates the application functionality:

![Animation cycles through signing into the app, clicking on buttons, and updating blog posts.](./Assets/14-mvc-homework-demo-01.gif) 

## Getting Started

Your application’s folder structure must follow the Model-View-Controller paradigm. You’ll need to use the [express-handlebars](https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js for your Views, use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect to a MySQL database for your Models, and create an Express.js API for your Controllers.

You’ll also need the [dotenv package](https://www.npmjs.com/package/dotenv) to use environment variables, the [bcrypt package](https://www.npmjs.com/package/bcrypt) to hash passwords, and the [express-session](https://www.npmjs.com/package/express-session) and [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize) packages to add authentication.

**Note**: The [express-session](https://www.npmjs.com/package/express-session) package stores the session data on the client in a cookie. When you are idle on the site for more than a set time, the cookie will expire and you will be required to log in again to start a new session. This is the default behavior and you do not have to do anything to your application other than implement the npm package.

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following:

    * Application’s folder structure follows the Model-View-Controller paradigm.

    * Uses the [express-handlebars](https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js for your Views.

    * Application must be deployed to Heroku.

### Technical Tools 

Connects to a MySQL database using the MySQL2(https://www.npmjs.com/package/mysql) and Sequelize(https://www.npmjs.com/package/sequelize) packages.

Stores sensitive data, like a user’s MySQL username, password, and database name, using environment variables through the dotenv(https://www.npmjs.com/package/dotenv) package.

## License

![license](https://img.shields.io/badge/license-MIT-blue.svg)

## 📝 Notes

- These are the (2) items required for submission
  1.  The url ling to Heroku deployment
      https://github.com/phagn131/e-commerce-back-end 
      
  2.  The URL of the GitHub repository that contains your code
      https://github.com/phagn131/e-c

## Contact Information:
- Github: [phagn13@github.com](https://github.com/phagn13@github.com)
- Email: [chloetechnologies@gmail.com](user@email.com)
