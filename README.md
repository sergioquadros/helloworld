#helloworld
#Some tips & tapas
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


__________________________________________________________________

Another way by Yvette BonvalotSignature in Exploratory Data Analysis/Coursera/2014-12-06:
OK here are the commands you can follow step by step (Windows systems):

1) Open your GitHub account
2) Now go to rdpeng's Github account: https://github.com/rdpeng/ExData_Plotting1
3) Fork rdpeng's ExData_Plotting1 repo to your github account (just click the FORKbutton)
4) On your PC, Load git bash
5) Using git bash on your PC, go where you want your github repo to be forked or copied (using change directory (or cd command, etc.)
6) Then use git clone to copy the forked github repo to your local drive with a command line like:
git clone https://github.com/YourGitHubAccountName/ExData_Plotting1
7) Now, be sure to go to that directory in git with: "cd ExData_Plotting1"
8) With Windows Explorer:
Copy the 4 R-scripts ypu developed in the ExData_Plotting1 directory and the 4 png files you created in the ExData_Plotting1/figures subdirectory
9) Go back to git
10) To check what happened you can type: git status
11) Add the files you put in those directories using:
"git add plot1.R plot2.R plot3.R plot4.R"
"git add figures/plot1.png figures/plot2.png figures/plot3.png figures/plot4.png"
12) do a small commit with git commit:
"git commit"
bla bla bla
13) Then exit that commit window by pressing ESC and then typing :wq.
14) git push your files to your remote github repo:
"git push origin master"

Hope this will be helpful
