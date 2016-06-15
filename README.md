# bin
OneStop script shell repo


About:
---
#####This shell script will automatically create the following directories where you run OneStop:
- js
- css
- scss
- gulpfile.js
- This will also run the command line to install "Bourbon" and "Neat" Sass dependencies in scss folder.

#####Files to be created/stored in their respective folders.:
-  "index.html" HTML5 file with simple skeleton (text includes: commented out \<script src= JQuery & Underscore \/\>, \<link href=main.css \/\>, and \<script src=app.js \/\>).
-  "main.scss" SASS file (text includes: "@import bourbon; @import neat;").
-  "app.js" JavaScript file (commented out text allows for ES6 functionality)

####Gulp and Gulp plugins (gulp-sass, gulp-ng-annotate, gulp-browser, and gulp-uglify) installed to your project directory.

INSTALLATION:
---
###Edit $PATH
Clone this repo within your User folder.
Wherever the repo is cloned, you will want to edit your $PATH so that the shell will know to look in this folder for the OneStop script using the command line code below:

<code>export PATH=$PATH:~/bin/</code>

Make sure to verify this directory has been added by command line code: <code>echo $PATH</code> and make sure your new directory was added.
After ensuring proper installation, go to the directory and clone your repo.

###Make sure you have execute privileges added to this file.
While in the bin directory, you need to make the script executable. To do so, use the following shell command:

<code>chmod +x onestop</code>

TO RUN:
---
Now you can use the OneStop script within any given directory to create your basic skeleton for a new project. To do this, just call the OneStop script:

<code>~/bin/onestop</code>
