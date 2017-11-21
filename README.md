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
  - __js__
    - init.js
    - jquery.dropotron.min.js
    - jquery.min.js
    - jquery.onvisible.min.js
    - jquery.scrolly.min.js
    - skel-layers.min.js
    - skel.min.js
  - __sidebars__
    - left-sidebar.html
    - no-sidebar.html
    - right-sidebar.html



You can check the build here: http://kaira.one/helios_jekyll

Unlike the original theme, users can change the content of the "Post" and "Article" directly under the _post directory. You can add as many posts you want, and you can even change the image by inputting a different file picture. All you have to do is create a new post with the proper file heading: ```YEAR-MM-DD-FILENAME.markdown``` and include this on the header.

```
---
layout: default
title: Post 1
desc: This is a sample post that is added under the "desc" part of the YAML.
img: pic01.jpg
categories: carousel
---
```
