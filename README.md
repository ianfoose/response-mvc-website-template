# Responsive Website Template

A website template that uses jQuery and Bootstrap 

## Setup

Install as the root of your website directory or wherever you need it under your project directory.

## Features

- The MVC Template features a reusable header and footer
- Global style and resources
- Resuability

## Use

### Directory Structure

All the javascript files are located under the 'js' directory, the main file is 'main.js'
All CSS files are under the 'css' directory, the main CSS file is 'style.css'
All header fiels are located under the 'inc' directory.

It is recommend that if you will be using images to make an 'img' directory i nthe root of the project. 

### Header Files

The file 'mainheader.inc.php' contains all the includes, such as jQuery and javascript and css files that would usually be found in the ```<head>``` section of your html, include any global includes here.

The file 'header.inc.php' is where you should put your main navigation menu and any navigation logic.

The file 'footer.inc.php' is where all footer elements and loginc will go.

Include 'header.inc.php' and 'footer.inc.php' on any pages you wish to carry over the the site theme on.  If you wish to to break the navigation and footer but keep the theme and associated resources then simply include 'mainheader.inc.php' instead of the header and or footer files.
