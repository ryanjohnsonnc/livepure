# Live Pure Static Site

This project uses to compile Sass into CSS, along with Autoprefixer and Browser Sync. It makes it easier to write neat code. We will probably build on it.

## Project Setup

Make sure you have Node and Gulp on your machine

Clone this repo to your local computer 

With the files downloaded, navigate to the project folder and run `npm install` to set things up.

If that doesn't work, try to use `sudo npm install`. I don't recommend it because it means something is probably jacked up with your Node setup.

With this set up, you should now be able to run:

    gulp

This will process any Sass (SCSS) files and launch a web browser showing the current files. Making changes to the files should result in the page updating automatically.

When you're all set up to deploy, you can run:

		gulp deploy
		
This will push the master branch to our gh-pages branch it will be viewable there.

