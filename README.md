# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* This repository is one of several sample templates for showcasing to clients. The templates are forks of
  [this master repository](https://bitbucket.org/carawebs/cw-master). Because they are forks of the master repository if you wish to add a file to all of the templates, you just add it to the master repository and then sync to the forks in bitbucket. Just go the fork in bitbucket and you'll be able to see how many commits you are behind the master and you'll be given an option to sync the changes. If you edit a file in the master repository that you have also edited in your fork, attempting to sync the changes will create a merge conflict. You'll need to manually integrate the changes to the forks. A selection of these templates should be displayed to the client, all slightly different. When the client selects which template to use, it should then be cloned and that clone will be the clients site. This means that the clients site will be a standalone clone of whichever fork they happen to like the most, so there will be no worrying about keeping the clone up to date with the changes made to the master repository.

### Explaination of workflow ###

Disclaimer!!! This might not be the best way to structure the workflow, but it's the best I can think up at the moment.

* The templates are forks of the master repository in order to facilitate some kind of uniformity between templates. The templates all follow the same
  base structure from the master. The templates are forks instead of branches as using branches would be bad practice as branches are used for small changes that are going to be merged in the future, whereas the forks are not going to be merged back into the master branch. As far as I know syncing the forks with the master is the best viable option for integrating changes from the master, as rebasing changes the commit that the fork is based on. Rebasing would create merge conflicts or overwrite changes, as the fork would contain changes that would conflict with changes on the master. Basically the master branch should be changed as little as possible, and any changes would ideally involve creating new files or editing files that have been untouched in the forks.

### How do I get set up? ###

* Clone the template

  Move to your new directory, change the baseurls in the config files to your new baseurl and run these commands:

* sudo npm install
* bower install
* mv HINTGruntfile.js Gruntfile.js
* grunt
