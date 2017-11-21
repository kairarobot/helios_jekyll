# Helios Jekyll Version

<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/mit-license-brightgreen.svg" alt="mit license"></a>
<a href="https://www.ruby-lang.org/en/downloads/"><img src="https://img.shields.io/badge/ruby-2.0.0-red.svg" alt="ruby version"></a>
<img src="https://img.shields.io/badge/platform-osx%20%7C%20linux%20%7C%20unix-lightgrey.svg" alt="versions">
<a href="https://www.npmjs.com/"><img src="https://img.shields.io/badge/npm-1.4.28-yellowgreen.svg"></a>

This is a Jekyll version of the theme Helios: http://html5up.net/helios

- __helios_jekyll__
  - _config.yml
  - ___layouts__
    - default.html
    - style.css
  - ___includes__
    - banner.html
    - carousel.html
    - __css__
      - main.css
      - skel.css
    - features.html
    - footer.html
    - head.html
    - header.html
    - js.html
    - main.html
  - ___posts__
    - __carousel__
  - __css__
    - font-awesome.min.css
    - __ie__
      - PIE.htc
      - backgroundsize.min.htc
      - html5shiv.js
      - v8.css
    - __images__
      - arrow.svg
    - skel.css
    - style-mobile.css
    - style-narrower.css
    - style-normal.css
    - style-noscript.css
    - style-wide.css
    - style.css
  - __images__
  - index.html
  - left-sidebar.html
  - no-sidebar.html
  - right-sidebar.html
  - __js__
    - init.js
    - jquery.dropotron.min.js
    - jquery.min.js
    - jquery.onvisible.min.js
    - jquery.scrolly.min.js
    - skel-layers.min.js
    - skel.min.js




You can check the build here: http://kaira.one/helios_jekyll

In the original Helios theme, the content is not abstracted. With this Jekyll theme, content can be managed (adding, deleting, or changing) under the `_posts` and `carousel` directories. 

<strong>Adding Post Articles</strong>
The main articles are located above the footer of the page. When a new article is created, the most recent one will show up to the left of the previous articles.
* To add an article create a new file under `_posts`  
* Make sure the file name follows this format `2015-01-01-post1.markdown` (```YEAR-MM-DD-FILENAME.markdown```)


<strong>Adding Carousel Articles</strong>
The carousel articles are located below the banner of the page. When a new article is created, the most recent one will show up to the left of the previous articles.
* To add an article create a new file under `_posts --> carousel`  
* Make sure the file name follows this format `2015-01-01-post1.markdown` (```YEAR-MM-DD-FILENAME.markdown```)
* There is also an option for changing the image of the article. The format for the carousel card is shown below:

```
---
layout: default
title: Post 1
desc: This is a sample post that is added under the "desc" part of the YAML.
img: pic01.jpg
categories: carousel
---
```
