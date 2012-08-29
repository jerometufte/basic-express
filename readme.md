## Basic Minimal Express Template for Heroku

This project is designed to rapidly deploy a simple one page app on node server to Heroku.

##  To deploy

Heroku's instructions are great https://devcenter.heroku.com/articles/nodejs  
If you're familiar with heroku, here's the short story:  
- make sure ur logged into heroku and init a git repo 
- `$ heroku create`  
- `$ git push heroku master`  
- `$ heroku ps:scale web=1`  
- `$ heroku ps`  
- `$ heroku config:add NODE_ENV=production`  
- check `$ heroku logs` or head straight to the provided url  
