# blog-application
Link - https://blog-app-039.herokuapp.com/
## Description:
A simple blog app where anybody can write down anything helpful so everyone can view. Fully implemented and user experience improved by security authentication and authorization.<br />

### Setup MongoDB

mongoose.connect("mongodb+srv://dbuser:dbpassword@cluster0.0heuv.mongodb.net/blog-site");
```
### NPM Install
```
npm install  
node app.js
```
- express (Server-side Javascript)
- ejs (Embedded Javascript)
- body-parser 
- mongoose (mongoDB for Express version)
- method-override (used for method PUT and DELETE in RESTful ROUTE that form type in cliend-side doesn't support
- connect-flash (middleware: store message displayed for user once and cleared after page being refreshed)
- passport
- passport-local
- passport-local-mongoose
- express-session

### Blog Index
* Setup the Blog App
* Create the Blog model
* Add INDEX route and template
* Add Simple Nav Bar
### Basic Layout
* Add Header and Footer Partials
* Include Semantic UI
* Add Simple Nav
### Putting the C in CRUD
* Add NEW route
* Add NEW template
* Add CREATE route
* Add CREATE template
### SHOW
* Add SHOW route
* Add SHOW template
* Add links to show page
* Style show template
### Edit/Update
* Add EDIT route
* Add EDIT form
* Add UPDATE route
* Add UPDATE form
* Add Method-Override
### DESTROY
* Add Method-Override
* Add EDIT and DESTROY links
### Create comments
* Update/Edit route + form
* Destroy route
### Create Authentication 
* register
* login
* logout
* hide/show links if user has logged in or not
* Authenticated author
### Finalize by adding Authorization
* User can only edit his/her campground
* User can only delete his/her campground
* Hide/Show edit and delete buttons
### Authorization for Post + Comment
### Refactor of Models, Views and Middleware
### Flash Message Adding
* Install and configure connect-flash -->
