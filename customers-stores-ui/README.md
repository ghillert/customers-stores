Customer Stores User Interface
==============================

## How to Run

Right now the easiest way to run the UI is to use Spring Boot.

    $ spring run app.groovy
    
and visit [http://localhost:9900](http://localhost:9900).

## How to Build

You can also serve the UI using Grunt. As a prerequisite you need to have NPM and Bower installed:

Next, install all dependencies needed (try with `sudo` and `-g` if this doesn't work):

	$ npm install
    $ npm install bower
	$ bower install

Now you can start the UI using:

	$ grunt serve




