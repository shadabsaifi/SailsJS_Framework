# SailsJS Framework

## https://www.quora.com/How-can-I-use-auto-generate-REST-API-with-SailsJS
## https://www.codementor.io/codeforgeek/how-to-setup-sailsjs-tutorial-beginners-du107nl5i

# You can then install stable version of Sails using following command:
    $ npm install -g sails or npm i sails -g 

# Now lets create a Sails application
	$ cd Desktop
	$ sails new projectName
# Install all the required packages needed to run your new project.

	$ npm install

# Start sails server with following command:

    $ sails lift
	


# Now, lets create simple REST API for User model with attributes name and email.

	$ sails generate api users name email

# Choose 2 (i.e the alter option) and press enter. Now the REST API is ready to use! So easy!

	Following are the routes which we can use. It deals with JSON data.
    GET /users
    GET /users/:id
    POST /users
    PUT /users/:id
    DELETE /users/:id
	
# Database Connection with mongodb

 ## To connect mongoDB 

	$ npm install sails-mongo






a [Sails v1](https://sailsjs.com) application


### Links

+ [Get started](https://sailsjs.com/get-started)
+ [Sails framework documentation](https://sailsjs.com/documentation)
+ [Version notes / upgrading](https://sailsjs.com/documentation/upgrading)
+ [Deployment tips](https://sailsjs.com/documentation/concepts/deployment)
+ [Community support options](https://sailsjs.com/support)
+ [Professional / enterprise options](https://sailsjs.com/enterprise)


### Version info

This app was originally generated on Tue Oct 30 2018 12:34:20 GMT+0530 (IST) using Sails v1.0.2.

<!-- Internally, Sails used [`sails-generate@1.15.28`](https://github.com/balderdashy/sails-generate/tree/v1.15.28/lib/core-generators/new). -->



<!--
Note:  Generators are usually run using the globally-installed `sails` CLI (command-line interface).  This CLI version is _environment-specific_ rather than app-specific, thus over time, as a project's dependencies are upgraded or the project is worked on by different developers on different computers using different versions of Node.js, the Sails dependency in its package.json file may differ from the globally-installed Sails CLI release it was originally generated with.  (Be sure to always check out the relevant [upgrading guides](https://sailsjs.com/upgrading) before upgrading the version of Sails used by your app.  If you're stuck, [get help here](https://sailsjs.com/support).)
-->

