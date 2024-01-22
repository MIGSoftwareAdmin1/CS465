# CS465
Added app_server folder to support full dynamic routing for the web app. Edited the template code in app.js to make sure that hbs is called as a library before the partials are registered. Sent a note to provider of hbs MVC template on that also. Will need to explicitly install both express-handlebars and hbs in shell before it will compile the web app using the following commands:
npm install express-handlebars
npm install hbs

I did test that the web app now fully compiles following these changes. If an issue persists locally, try running npm audit fix --force
