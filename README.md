# note-taker11

1. This Note Taker app was created with the purpose of providing busy people with an easy and reliable way to keep track of their to-dos, thoughts, appointments, etc. By accessing it online, the user will be able to do the following:

2. Write new notes within the provided title and text fields on the right-side of the screen.

3. Saving the notes to a database if they so desire it.

4. Empty the fields in order to write a new note.

5. Select an already saved note from the rendered list of notes retrieved from the database in order to inspect it on the note-pad area to the right.

6. Delete an already saved note if the user no longer has any use for it.

7. For its author, the challenge was an instructive way to :

8. Practice modularization as a way to implement separation of concerns when coding the back-end of the application. In this case, different endpoints get their own node module, and so do custom middleware and helper functions.

9. Continue learning about the connection between different methods of request (get, post, and delete) using the Fetch API on the front-end and the different routes (including some that utilize Express.js routers) defined on the back-end.


# Installation

N/A: The full stack application is actually a website deployed to Heroku. See "Credits" section for more information.


# How to Contribute

If you want to contribute, feel free to fork the repo, modify the repo on your local machine and then open a pull request. That way I can review the changes before deciding whther to merge them in the codebase or not.


# credits


The project is of the authorship of Jonathan Maldonado.The GitHub repo can be found at: https://github.com/MaitreePatel08/note-taker11.git

The app is deployed on Heroku at: 

The .gitignore file was lifted from the GitLab class repo found at: https://git.bootcampcontent.com.

The starter code for the app (providing its front end), can be found at: https://github.com/coding-boot-camp/miniature-eureka

The front-end part employs both the Bootstrap CSS framework and the Font-Awesome third party icon API. Links to the respective libraries are below:

https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css

https://use.fontawesome.com/releases/v5.3.1/css/all.css

The folder structure of the project and the helper functions and custom middleware has been adapted from those found in the activities and Mini-Project for the Module 11 of the Rutgers Full Stack Bootcamp.

This app works in the Node.js JavaScript runtime environment. The latest stable (recommended version) can be found at: https://nodejs.org/en/download

We import and make use of the built-in modules "path", "fs" and "util" from the standard library.

We use npm for the specification (semantic versioning) of the app's dependencies and their installation. Here is the URL for the official site of the npm registry: https://www.npmjs.com

In particular, we added "express": "^4.16.4"(in order to create and work with servers, middleware, routers, etc.), "path-to-regexp": "^6.2.1" (initially a sub-dependency in the node-modules folder that was updated to get rid of some error messages in the terminal), and "uuid": "^8.3.2" (from this one we just import the v4 function (renamed uuidv4 within the project) so as to give each note a universally unique identifier ) to the Dependencies . You can find the most recent versions of the node packages here:

https://www.npmjs.com/package/express for Express; https://www.npmjs.com/package/path-to-regexp for Path-to-RegExp; and https://www.npmjs.com/package/uuid for UUID.