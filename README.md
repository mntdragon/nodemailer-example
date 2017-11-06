nodemailer-example


-clone this
-npm install
-edit the user and pass become your own gmail
-make sure to allow the Less secure apps via google from your gmail
--- Go to : https://www.google.com/settings/security/lesssecureapps
set the Access for less secure apps setting to Enable

****************first steps in the beginning when creating
npm init
npm install --save nodemailer express
npm install nodemon --save-dev //To get rid of every time restart the server, we are using one package called nodemon server.

--In the root directory, create one js file called server.js
--modify start script in a package.json file.
"scripts": {
    "start": "nodemon server"
  },

npm install --save ejs //using EJS as a templating engine

--create public folder 
	 views folder(hold ejs file)
********************************
