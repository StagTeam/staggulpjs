# [staggulpjs](https://www.staglabel.be)
[![Build Status](https://travis-ci.org/staglabel/staggulpjs.svg)](https://travis-ci.org/staglabel/staggulpjs)
[![devDependency Status](https://david-dm.org/staglabel/staggulpjs/dev-status.svg)](https://david-dm.org/staglabel/staggulpjs#info=devDependencies)


StagGulpJS is a js builder starter based on gulp, Bower, that will help you make better build js.

* Source: [https://github.com/staglabel/staggulpjs](https://github.com/staglabel/staggulpjs)



## Requirements

| Prerequisite    | How to check | How to install
| --------------- | ------------ | ------------- |
| Node.js 0.12.x  | `node -v`    | [nodejs.org](http://nodejs.org/) |
| gulp >= 3.8.10  | `gulp -v`    | `npm install -g gulp` |
| Bower >= 1.3.12 | `bower -v`   | `npm install -g bower` |

For more installation notes, refer to the [Install gulp and Bower](#install-gulp-and-bower) section in this document.

## Features

* [gulp](http://gulpjs.com/) build script, checks for JavaScript errors, optimizes images, and concatenates and minifies files
* [Bower](http://bower.io/) for front-end package management
* [asset-builder](https://github.com/austinpray/asset-builder) for the JSON file based asset pipeline


## Installation

Clone the git repo - `git clone https://github.com/staglabel/staggulpjs.git` and then rename the directory to the name of your theme or website.



## Configuration


### Install gulp and Bower

Building requires [node.js](http://nodejs.org/download/). We recommend you update to the latest version of npm: `npm install -g npm@latest`.

From the command line:

1. Install [gulp](http://gulpjs.com) and [Bower](http://bower.io/) globally with `npm install -g gulp bower`
2. Navigate to the theme directory, then run `npm install`
3. Run `bower install`

You now have all the necessary dependencies to run the build process.

### Available gulp commands

* `gulp` — Compile and optimize the files in your assets directory
* `gulp watch` — Compile assets when file changes are made
* `gulp --production` — Compile assets for production (no source maps).
