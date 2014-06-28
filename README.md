# Foundation Compass Stack
### A Foundation template on steroids!

This is a template for your next web project using Foundation, Grunt, Compass, and Assemble!

## Requirements

You'll need to have the following items installed before continuing.
	
* [Ruby](http://ruby-lang.org/): If you are on OSX or Linux, you should already have Ruby installed. If not, check their website for installation options.
* [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
* [Grunt](http://gruntjs.com/): Run `sudo npm install -g grunt-cli`
* [Bower](http://bower.io): Run `sudo npm install -g bower`
* [Sass](http://sass-lang.com) & [Compass](http://compass-style.org): Run `gem update --system && gem install compass`


## Quickstart

Clone this repository:
`git clone git@github.com:zurb/foundation-compass-stack.git`

Navigate into the directory:
`cd foundation-compass-stack`

Install all the dependincies:
`npm install && bower install`

While you're working on your project, run:

`grunt`

This will assemble all the pages and compile the Sass. You're set!

## Directory Structure

* `dist`: Static pages are assembled here. This is where you should view the site in your browser. **Don't edit these files directly. They will be overwritten!**
* `src`: This is the directory you'll work in. 
* `src/assets`: All assets (scss, images, fonts, js, etc) go here.
* `src/assets/scss/_settings.scss`: Foundation configuration settings go in here
* `src/assets/scss/app.scss`: Application styles go here
