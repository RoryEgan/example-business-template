# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* This repository is a simple Jekyll site that could be used as a business template. The site uses Sass and Grunt. The pages that are currently available are the Homepage, About page, Contact page and a simple Blog page. The Frontpage and Contact page both include google maps. Data such as business name, phone number etc. are brought through via csv spreadsheets rather than the traditional method of through the config file. It is done this way in order to send a hypothetical client a spreadsheet which is returned and put straight in to the `_data` file rather than the information having to be manually entered into the config file.

### How do I get set up? ###

* Clone the template
* Move to your new directory, change the baseurls in the config files to your new baseurl and run these commands:

```
 npm install
 bower install
 mv HINTGruntfile.js Gruntfile.js
 grunt
```

You should now be good to go!
