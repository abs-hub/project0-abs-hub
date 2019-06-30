# Project 0

CS50’s Web Programming with Python and JavaScript

## Requirements

Click [here](https://github.com/abs-hub/project0-abs-hub/blob/master/REQUIREMENTS.md) to view the requirements.

## Tech Design and component list

* The project consists of 4 html file, one SCSS file and one custom style sheet. It uses Bootstrap 4.3.1, googleapis font Open Sans and font-awesome v 4.7 to show icons on home page and contact.html page.
* The html pages can be access from any page on the website. The social media links will redirect you to my facebook, twitter, linkedin and personal blog.
* Below is the component list and its details:
<table>
   <thead>
      <tr>
         <th><strong>File</strong></th>
         <th><strong>Description</strong></th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td><code>index.html</code></td>
         <td>This is the home page for website, features: <br/> &bull; Unordered list navbar, leveraged using Bootstrap<br/> &bull; Full width container grid with two columns. <br/> &bull; The image borders behavior changes for small screen devices. This is done using <strong>@media</strong> query. <br/> &bull; Used SCSS inheritance and nesting on <strong>.social, .social ul, .social li</strong> <br/> &bull; Used custom stylesheets, present in main.css and has over five different CSS properties. Have used #id and .class selectors.</td>
      </tr>
      <tr>
         <td><code>projects.html</code></td>
         <td>This page contains the list of projects displayed using 3 column full width grid. It has 3 different images with linear-gradient background. Refer computedStyle.scss to view the colors used for gradient in $project-gradient variable</td>
      </tr>
      <tr>
         <td><code>certs.html</code></td>
         <td>This page shows list of Certificates and uses Bootstrap carousel to show automatic sliding effect. I have done small tweak to make the caption go below the image. The tweak is to make <code>{ position: relative; }</code> for carousel-caption. The carousel-caption heading font size is reduced to 1rem for screens up to 576px using <strong>@media</strong> query.</td>
      </tr>
      <tr>
         <td><code>contact.html</code></td>
         <td>This page has a table and uses Bootstrap table class. I have used custom styling to make the table margin auto and text aligned center.</td>
      </tr>
      <tr>
         <td><code>computedStyle.scss</code></td>
         <td>This is the SCSS file and has used SCSS variable to apply colors and fonts. It also applies the concept of SCSS nesting and SCSS inheritance. This file is present under css folder.</td>
      </tr>
      <tr>
         <td><code>computedStyle.css</code></td>
         <td>This is the CSS file generated using SASS. Locally I have used this command to auto compile and generate the CSS file: <br/><code>sass --watch computedStyle.scss computedStyle.css</code> <br/> This file is present under css folder.</td>
      </tr>
      <tr>
         <td><code>computedStyle.css.map</code></td>
         <td>This is a source map file in JSON format which got generated when SCSS file was compiled into CSS. It contains information that links each line of your computedStyle.css file to the corresponding line in computedStyle.scss. This file is present under css folder.</td>
      </tr>
      <tr>
         <td><code>main.css</code></td>
         <td>This is the websites stylesheet file. It contains common CSS and page specific CSS. This file is present under css folder.</td>
      </tr>
      <tr>
         <td><code>images</code></td>
         <td>This is a folder and contains images used in the website. Few images are my personal images and few are taken from <a href="https://unsplash.com">https://unsplash.com</a>.</td>
      </tr>
      <tr>
         <td><code>README.MD</code></td>
         <td>This file contains html table to describe the component list which we are reading. The source code is combination of Markdown and HTML.</td>
      </tr>
      <tr>
         <td><code>REQUIREMENTS.MD</code></td>
         <td>This file content is taken from the requirements provided by Professor and is translated to Markdown language. </td>
      </tr>
   </tbody>
</table>

## Demo
Click [here](https://abs-hub.github.io/project0-abs-hub/) to view the published website.
