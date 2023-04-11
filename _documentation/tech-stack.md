---
layout: "default"

title: "Tech stack"
---

## SASS

Styling is powered with Sass, a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets (CSS).
Style files are located in the `resources/sass` folder.

**Useful links**

- [Install Sass](https://sass-lang.com/install)

### Compiler file

All scss files are imported into the `app.scss` file. This means that whenever you create a new `.scss` file, you need to add the path to that file to `app.scss`. 

This file then compiles all the files into one single `.css` file, readable by the browser.