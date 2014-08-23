#helloworld
==========
##My first repository on GitHub.
=========
###Create a new repository on the command line

* touch README.md
* git init
* git add README.md
* git commit -m "first commit"
* git remote add origin https://github.com/sergioquadros/datasciencecoursera.git
* git push -u origin master

###Push an existing repository from the command line

* git remote add origin https://github.com/sergioquadros/datasciencecoursera.git
* git push -u origin master

###Import code from an old repository

###You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
==================================
##From https://class.coursera.org/datascitoolbox-006/forum/profile?user_id=1327050
* while logged into GitHub in a web browser, forked the GitHub repository datasciencecoursera from the instructor's GitHub account
* executed the command: git clone https://github.com/your_git_account/datasciencecoursera
* executed the command: cd datasciencecoursera
* created a text file named 'HelloWorld.md' using RStudio (or any text editor)
* executed the command: git add .   # note the dot at the end of the command
* executed the command: git commit -m "a message here"
* executed the command: git push origin master
* verified MyFile.md appears in your remote repository on GitHub
