# elliotackland

    
> Material Design Lite being introduced


This project is all about recycling and renewing skills to meet current market requirements.


## Install Packages

After cloning the project to your computer run the following command in your terminal to install all required node and bower packages.

	1.  npm install && bower install


## Start

	gulp

## Build

Create a deployment build with the following commands:

	gulp build


## Features

- Uglify: Minification js
- Cssnano: Minification css
- BrowserSync
- Gulp Sass: Converts sass to css
- Nunjucks: Templating

## How to use

Precompiled JS, SCSS and image files are in the app/assets folder and compile to dist.  All other files including HTML/Nunjucks (layouts, pages, partials) are in app.  BrowserSync runs from app and serves as the "Dist" folder for client-side apps.


## To Do
- more testing
