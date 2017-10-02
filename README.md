MDWiki modified by @elliptic\_shiho
=========

**Caution: Almost all files are Modified Version from Original MDWiki!!**

Disclaimer: Firstly, I modified this for personal use, so I didn't check licenses mathjax and mdwiki.
If you want to use this, I don't responsible any problem of licenses.


## Modified Point
* Support MathJax (If you use it, you must place mathjax files at `/mathjax/MathJax.js` )
* Changed Content files path ( `/content/hoge.md` -> `mdwiki.html#!/hoge.md` )
* Don't use CDN at Theme Styles (e.g. To use `flatly` theme, You must place `/theme/flatly/~~~` then you can use  `[gimmick:Theme](flatly)` )
  - TODO: Can use any themes

Below is original readme:

---

[![Build Status](https://travis-ci.org/Dynalon/mdwiki.png?branch=master)](https://travis-ci.org/Dynalon/mdwiki)


MDwiki
======

100% static single file CMS/Wiki done purely with client-side Javascript and HTML5.

See http://www.mdwiki.info for more info and documentation.
------


Download
--------

See <https://github.com/Dynalon/mdwiki/releases> for readily precompiled releases.

How to build from source
------------------------

1. Install node.js >= 0.8 and npm (if not included)
2. Clone this repo
3. Install deps:

    npm install

4. Install components

    bower install

    (or if not installed globally)
    ./node_modules/.bin/bower install

5. Build MDwiki

    grunt release

    (or if not installed globally)
    ./node_modules/.bin/grunt release

6. Find the `mdwiki.html` in the `release/` and `dist/` folder



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Dynalon/mdwiki/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

