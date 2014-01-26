# Creating a new page

The web site uses [Clean URL](http://en.wikipedia.org/wiki/Clean_URL)s for pages, so the (1) step is to create folder with the name of the new page and create file with `index.textile` name. The (2) next step is to add a special header in the beginning of the file and to replace `<page name>` with the page name (spaces are allowed):

```
---
layout: page
title: <page name>
---
```
The (3) step is to writing content in [Textile](http://redcloth.org/hobix.com/textile/quick.html), you can use [Textile live web editor](http://borgar.github.io/textile-js/) to see the result immediately. Once you finished (4) commit the folder and the file in the repository, they will accessible in a few seconds.

# Running the jekyll server on a local machine

`jekyll serve --watch --config _config.development.yml, _config.yml`

# Contacts

Maxim Kolchin (kolchinmax@gmail.com)
