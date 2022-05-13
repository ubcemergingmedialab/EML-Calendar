# EML-Calendar


Scripts and stylesheets for the EML Calendar.

This is not a functional project on its own. It's necessary to compile the JS and CSS, then manually copy the resulting code into WordPress, or whatever other platform is being used.

Instructions for integrating with https://eml.ubc.ca/calendar:


Stylesheets:
------------
Use SASS: 
https://www.npmjs.com/package/sass

Once installed, do:
sass --watch sass:css

This compiles to the CSS directory.
Don't know SASS? Great! We use SCSS syntax. Don't know what that is? Great! You can write SCSS just like normal CSS and ignore the extra features. Just remember to put it in the .scss files, and NEVER PUT IT IN THE .CSS files.

The entire /css directory is write-only. Never, ever, ever edit them, because they get overwritten when compiling CSS.