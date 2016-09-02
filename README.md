# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

  This repository is a multi-page jekyll template. The frontpage is organised through a series of sections that get inline style rules to
  determine background image, image opaque overlay and light or dark text. The frontmatter of each section determines what layout that section
  will follow and what, if any, backgound image, colour, or opacity the section gets.

  The site services and projects are both organised into
  collections, and their respective pages will loop through their collection to detect existing services and projects. Client information is entered
  through several .csv spreadsheets in the data of the site.

  The grunt imageManifest task will auto-generate refernces all existing images in the images
  folder(including any subdirectories) into the image-manifest.yml file. The task will also give an image a category based on where it is situated. For
  example an image inside "assets/images/medium-images" will be automatically given the category "images-medium-images".

  The grunt imagecheck task is a task to compress and trim images. All initial images should be placed within a ```_source-images``` folder. The images should
  be arranged into two subdirectories, ```medium-images``` and ```big-images```.
  The task is run with the command ```grunt imagecheck```. The task scales the
  images within the big folder to a width of 1920px and the images in the medium
  folder to width of 720px. All images have their quality degraded to 70%. The task will then crop the big images to a height of 1064px and the medium images
  to a height of 460px. The newly processed images are moved to the ```/assets/images``` directory, with the task creating the subdirectories ```big-images``` and  ```medium-images``` if they do not already exist. If these subdirectories already exist and contain images that have the same name as the newly processed images, the task will overwrite the existing images to the processed version.

### How do I get set up? ###

* Clone the template

  Move to your new directory, change the baseurls in the config files to your new baseurl and run these commands:

* npm install (may require sudo)
* bower install
* cp HINTGruntfile.js Gruntfile.js
* grunt

Now navigate to your localhost to see the site!
