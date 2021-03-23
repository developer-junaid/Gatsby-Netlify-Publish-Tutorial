## Publish Simple Gatsby Site on Netlify using Netlify GUI, netlify.toml with CI/CD and Git.

## Site Deployed --> 🔗 https://gatsby-netlify-publish.netlify.app/

<center><img src='./src/images/homepage.png' /></center>

## Steps

- Signup on <a href='https://www.netlify.com/'>Netlify</a>
- run "npm init gatsby"
- Select options
- - what would you like to call your site? (write name "mysite")
- - what would you like to name the folder where your site will be created? (write name of folder "mysite")
- - Will you be using a CMS? (select "No or I'll add it later")
- - Would you like to install a styling system? (select "No, or I'll add it later")
- - Would you like to install additional features with other plugings? (select Done)
- - Shall we do this (write "y" and press enter)
- (navigate to directory)cd mysite
- create file (netlify.toml) on root
- add commands inside (as written in netlify.toml in my repo)
- commit and push app to github
- go to netlify
- click "new site from git"
- authorize
- select your repository
- click "deploy site"
- Open Website Url, and woohoo !! Your website is deployed
- Now if you make some change in your code
- - just make a change
- - commit it
- - push it and that will reflect in your hosted app automatically !!
