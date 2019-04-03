`create heroku`

to create a new heroku rep

`"scripts": {
    "start": "node app.js"  //may vary with tech used
  },`
  
  `"engines": {
    "node": "10.15.0"
  },`
  
Add the above to package.json to make app compatible with heroku

`git remote -v`

to confirm that a remote named heroku has been set for your app

`git remote rm heroku`

`git remote add heroku git@heroku.com:yourappname.git`

renaming heroku app
also, rename manually from heroku.com

`git push heroku master`

push rep t heroku

`heroku open`

to open app


