###Run dev
node src/index.js
___

###File's modification
1. TypeDefs
2. Datasources
3. Resolvers
___

###Routes
Change server.js routes

###Deployment
- heroku login
- heroku create "appName"
- heroku container:login
- heroku container:push web --app "appName"
- heroku container:release web --app "appName"

Uodate Connections
src/server.js