## Probable Happiness

[![Build Status](https://img.shields.io/travis/mayant15/probable-happiness?style=for-the-badge)](https://travis-ci.com/mayant15/probable-happiness)
[![Ruby](https://img.shields.io/badge/ruby-2.5.2-blue.svg?style=for-the-badge)](http://travis-ci.org/jekyller/jasper)
[![Jekyll](https://img.shields.io/badge/jekyll-3.6.2-blue.svg?style=for-the-badge)](http://travis-ci.org/jekyller/jasper)
[![Trivago](https://img.shields.io/badge/Hotel%3F-Trivago-important?style=for-the-badge&logo=Tinder)](https://travis-ci.com/mayant15/probable-happiness)

A blog for one of my clubs based on [Jasper](https://github.com/jekyller/jasper)

## Demo
Hosted by GitHub Pages [here](mayant15.github.io/probable-happiness)

## Jasper theme includes

* Pagination
* Google Analytics tracking
* Author's profile with picture
* Disqus comments (not Ghost standard)
* Author page (New 07.02.2015)
* Tag page(s) (New 07.02.2015)
* 404 page (New 07.02.2015)
* Toggleable sliding sidebar (New 07.02.2015)
* Related posts view (New 30.10.2015)
* Tag description(s) (New 30.10.2015)
* Code Syntax Highlight (New 24.11.2015)
* Code Syntax Highlight with [highlight.js](https://highlightjs.org/) (New 06.04.2016)
* Rss updated to Jekyll v3 (New 06.04.2016)
* Updated to Casper v1.3.7 **(New 17.11.2017)**  
* 'Out of the box' support for Multiple Authors **(New 17.11.2017)**  

### Deployment

**Important:**  For security reasons, Github does not allow plugins (under _plugins/) when deploying with Github Pages.

We build the site through Travis-CI and push the generated files to the `gh-pages` branch.

To setup, change your details in *[\_config.yml](_config.yml)* so that you can push to your github repo. You will also need to generate a secure key to add to your *[.travis.yml](.travis.yml)* (you can find more info on how to do it in that file). Also make sure you read the documentation from [jekyll-travis](https://github.com/mfenner/jekyll-travis). This approach has clear advantages in that you simply push changes to your files and all the html files are generated for you. Also you get to know if everything is still fine with your site builds.

### Author pages

In order to properly generate author pages you need to rename the field *categories* in the front matter of every post to match that of your each author *username* as defined in the *[\_config.yml](_config.yml)* file.
With the latest update, multiple author blogs are now supported out of the box.

## Copyright & License

Same licence as the one provided by Ghost's team. See Casper's theme [license](GHOST.txt).

Copyright (C) 2015-2017 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
