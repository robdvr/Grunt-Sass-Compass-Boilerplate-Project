Grunt-Sass-Compass-Boilerplate Project
======================================

A simple grunt project with live reloading, compass, sass, jshint, uglify, and connect.

Pull requests are welcome!

## Requirements
* npm (node package manager)
* Node.js
* Rubygems
* Sass
* Compass

If you need instructions on how to set this up, [look here.](http://robdvr.com/install-sass-compass-grunt/)

## How to use?
1. Clone this project
2. Install [LiveReload Browser Extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions)
3. Browse to the downloaded directory and install node modules:
  
  ```
  npm install
  ```
4. Run grunt to start the engines
  
  ```
  grunt
  ```
5. Navigate to local server
  
  ```
  http://localhost:8000/
  ```
6. Enable LiveReload Browser extension

7. Change any html/css/js file and enjoy!

## Production Build
If you decide to use the production mode, use the following command:
```
grunt build
```

Special thanks to [Rob Decker](http://chapterthree.com/blog/theme-development-grunt-livereload-lint-uglify-oh-my) for putting together the Gruntfile.js
  
