didthesaintswin
===============

Whodat bebe


This here bad boy was generated using Yeoman http://yeoman.io/. Directions on how to git dat hip workflow going are below (should have Node and probs some other things installed)....

####  Local Version
``` 
git clone git@github.com:alhertz/didthesaintswin.git
cd didthesaintswin
grunt server
```
####  Deploy to Github Pages
Right now the gh-pages branch is set up as a subtree that you can deploy too.
``` 
grunt build
git subtree push --prefix dist origin gh-pages
``` 
or if you want to just upload everything to another server via FTP or something like that. 
``` 
grunt build
``` 
For more help with deployment (like deploying to Heroku) peep these docs: http://yeoman.io/deployment.html
