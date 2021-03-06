# Testing Environment
This repo is for testing UX Designs using HTML and CSS in a static environment.

### Resources:
 - PatternFly 3
 - Bootstrap 3
 - Node
 - Bower
 - Gulp

## Prerequisites:
  <blockquote>
    This repo assumes that you have Node and Bower installed and know how to use each of those.
  </blockquote>
 - [Node.js](https://nodejs.org/en/)
 - [Bower.io](https://bower.io)

If you are using MacOS, I recommend using [Homebrew](http://brew.sh) for your package manager. You can download Nodejs v6(LTS) directly from there.

## Installation
* Step 1:
 - Fork and Clone the repo
* Step 2:
 - run `npm Install`
  <blockquote>
    this install the npm modules, which are required for the project to run
  </blockquote>
* Step 3:
 - run `bower install`
  <blockquote>
    this will install the bower components, which are required for the site to render
  </blockquote>
* Step 4:
 - run `gulp`
  <blockquote>
    this will run through all of the initial setup script setups<br />
    <strong>If there are errors with these scripts, please verify that you have NodeJS installed correctly</strong>
  </blockquote>

## Development &amp; Usage
 By running the default `gulp` command, all of the required library and component pieces will be moved over the the /dist directory. If you wish to build your SASS or JS as well, you can run either `gulp sass` or `gulp js`.
 
 If you wish to run the project in a local environment, you can enter the command `gulp serve`. This will start up a synchronized browser, which will automatically refresh upon any HTML, SASS, or JS change (utilizing the `gulp sass` and `gulp js` commands).
