# The website.
  
This repo is based off a jekyll template, "Jekyll One".  
I added the following:  
* .travis.yml
* cibuild
  
travis executes cibuild, which zips up the site and curls it to freejekyllbuilder.com.  
Then travis hits a deploy webhook on prod which triggers a deploy.
  
Let me know if you see this!  Thanks
