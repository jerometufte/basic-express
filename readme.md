## Basic Minimal Express Template for Heroku

This project is designed to rapidly deploy a simple one page app on node server to Heroku.

##  To deploy

#### Heroku's instructions are great https://devcenter.heroku.com/articles/nodejs  
#### If you're familiar here's the short story  
- `$ heroku login`  
- `$ git init`  
- `$ git add .`  
- `$ git commit -m "init"`  
- `$ heroku create`  
- `$ git push heroku master`  
- `$ heroku ps:scale web=1`  
- `$ heroku ps`  
- `$ heroku config:add NODE_ENV=production`  
- check `$ heroku logs`  
