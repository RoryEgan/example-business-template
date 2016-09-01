# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* This repository is a multi-page jekyll template. The frontpage is organised through a series of sections that get inline style rules to
  determine background image, image opaque overlay and light or dark text. The frontmatter of each section determines what layout that section
  will follow and what, if any, backgound image, colour, or opacity the section gets.

  The site services and projects are both organised into
  collections, and their respective pages will loop through their collection to detect existing services and projects. Client information is entered
  through several .csv spreadsheets in the data of the site.

  The grunt imageManifest task will auto-generate refernces all existing images in the images 
  folder(including any subdirectories) into the image-manifest.yml file. The task will also give an image a category based on where it is situated. For
  example an image inside "assets/images/medium-images" will be automatically given the category "images-medium-images".

### How do I get set up? ###

* Clone the template

  Move to your new directory, change the baseurls in the config files to your new baseurl and run these commands:

* npm install (may require sudo)
* bower install
* cp HINTGruntfile.js Gruntfile.js
* grunt

Now navigate to your localhost to see the site!
