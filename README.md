# Project 0

CS50’s Web Programming with Python and JavaScript

## Requirements

Click [here](https://github.com/abs-hub/project0-abs-hub/blob/master/REQUIREMENTS.md) to view the requirements.

## Tech Design and component list

* The project consists of 4 html file, one SCSS file and one custom style sheet. It uses Bootstrap 4.3.1, googleapis font Open Sans and font-awesome v 4.7 to show icons on home page and contact.html page.
* The html pages can be access from any page on the website. The social media links will redirect you to my facebook, twitter, linkedin and personal blog.
* Below is the component list and its details:
/***
| __File__ | __Description__ |
| --- | --- |
| `index.html` | This is the home page for website, features: <br/> &bull; Unordered list navbar, leveraged using Bootstrap<br/> &bull; Full width container grid with two columns. <br/> &bull; The image borders behavior changes for small screen devices. This is done using **@media** query. <br/> &bull; Used SCSS inheritance and nesting on **.social, .social ul, .social li** <br/> &bull; Used custom stylesheets, present in main.css and has over five different CSS properties. Have used #id and .class selectors. |
| `projects.html` | This page contains the list of projects displayed using 3 column full width grid. It has 3 different images with linear-gradient background. Refer computedStyle.scss to view the colors used for gradient in $project-gradient variable |
| `certs.html` | This page shows list of Certificates and uses Bootstrap carousel to show automatic sliding effect. I have done small tweak to make the caption go below the image. The tweak is to make `{ position: relative; }` for carousel-caption. The carousel-caption heading font size is reduced to 1rem for screens up to 576px using **@media** query.
| `contact.html` | This page has a table and uses Bootstrap table class. I have used custom styling to make the table margin auto and text aligned center.|
| `computedStyle.scss` | This is the SCSS file and has used SCSS variable to apply colors and fonts. It also applies the concept of SCSS nesting and SCSS inheritance. This file is present under css folder.
| `computedStyle.css` | This is the CSS file generated using SASS. Locally I have used this command to auto compile and generate the CSS file: <br/>`sass --watch computedStyle.scss computedStyle.css` <br/> This file is present under css folder. |
| `computedStyle.css.map` | This is a source map file in JSON format which got generated when SCSS file was compiled into CSS. It contains information that links each line of your computedStyle.css file to the corresponding line in computedStyle.scss. This file is present under css folder. |
| `main.css` | This is the websites stylesheet file. It contains common CSS and page specific CSS. This file is present under css folder. |
| `images` | This is a folder and contains images used in the website. Few images are my personal images and few are taken from https://unsplash.com. |
***/
## Demo
Click [here](https://abs-hub.github.io/project0-abs-hub/) to view the published website.
