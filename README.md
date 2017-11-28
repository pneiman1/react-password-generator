A password generator built with React and Express.

Phil Neiman's Deployed version: https://random-pass-gen.herokuapp.com/

This is using Create React App to bootstrap a React project, connect the React app to an Express backend, and deploy the whole thing to Heroku.

Read the blog post: Create React App with Express in Production

Prerequisites

You need to sign up for a Heroku account if you don't already have one, and install the Heroku toolbelt. (On a Mac with Homebrew, just run brew install heroku).

Deploy to Heroku

To deploy:

Clone this repo.
Inside the repo directory, run heroku create (requires Heroku toolbelt).
Run git push heroku master to simultaneously deploy the frontend + backend to Heroku.
Using NPM

Check out the npm branch if you're not using Yarn:

git checkout npm

And then once on that branch, the deploy command is:

git push heroku npm:master