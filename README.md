![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 05: Form Building Workshop
===
## Code Wars Challenge

Complete [Kata 1](https://www.codewars.com/kata/regex-validate-pin-code) and [Kata 2](https://www.codewars.com/kata/alternate-capitalization), then follow the submission instructions from Lab 01. Note that the instructions must be followed for *each* of these challenges.

## Lab 05 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[HighlightJS Docs](https://highlightjs.org/)

[MarkedJS Docs](https://github.com/chjj/marked)

## Configuration
_Your repository must include:_

```
05-form-building
└── starter-code
└── driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── README.md
  ├── index.html
  ├── new.html
  ├── scripts
  │   ├── article.js
  │   ├── articleView.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── default.css
          ├── icons.css
          ├── normalize.css
          └── railscasts.css
  └── PULL_REQUEST_TEMPLATE.md
  └── README.md
```


## User Stories and Feature Tasks

*As a user, I want to be able to add new articles to my blog app so that it can stay current over time.*

- Review the image `preview.png` in the lab directory to get an idea of what we will be building.
- Focus on the functionality of adding a new article through a form submission by completing the TODOs in articleView.js.
- The new page with the form should provide a JSON string which can be copy/pasted into the data file to add articles to the blog.

*As a developer, I want to make the user experience easy to understand so that the user will want to return to the blog.*

- We now have two pages in our blog app, each of which need different initialization. There is a skeleton of a method in articleView.js to get this started for the new page; be sure to examine how this is now being done for the index page.
- The new page with the form will need event handling and a template. Where should these pieces go in the code?
- The new page should not display any other articles; how to manage this?

### Stretch Goal
*As a user, I want to add highlighting and Markdown formatting so that it is attractive to guests visiting my app.*

- We have two new libraries that we can add: HighlightJS (provides syntax highlighting of code blocks) and MarkedJS (allows use of Markdown format text). Link to (or include) these two libraries and implement them.

## Documentation
_Your README.md must include:_

```md
# Kilovolt blog

**Author**: Tim McCoy
**Version**: 4.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
 This application is a blog that uses javascript to display content accordingly and implements a new html page that takes input nd coverts to a JSON string that can be copied into blogArticles and generated on the index.html page

## Getting Started
They'd access new.html directly and fill in the appropriate fields to generate their own article(s). Then they can pass that info into blogArticles.js to populate on the main page.

## Architecture
 HTML, CSS, jQuery, JSON, Ajax and Marked CDN links as well as CSS style pages and provided fonts/icons

## Change Log

04-13-2018 4:00pm - Coded 90% of form in lecture, added new article template

04-13-2018 5:00pm - Created new object array to hold new values, created JSON string to copy/paste into blogArticles

## Credits and Collaborations

 https://highlightjs.org/
 https://github.com/markedjs/marked
