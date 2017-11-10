# UIClassNovember09-2017
To demonstration tutorial on how to use git and github

to download this for the first time

git clone https://github.com/karthikkrishna611/UIClassNovember09-2017.git
 

After you make the changes in the code ,use command 
 
git add .
 
to commit your chnages to local repo : use command

git commit -m "commit message"


to send the information from local repository to remote repository use command 

git push --set-upstream origin branchname

to create a new branch out of existing branch use command

git checkout -b branchname

-b is flag for creating new branch to get existing branch use git checkout branchname

suppose if you have two branches 

feature and develop

suppose if you need to merge feature into develop: use following commands

before you start this commands make sure your develop branch is upto date my making a git pull on develop first and then start process below. Also make sure you commit all changes into feature and develop and then start process below.

git checkout feature 

git merge develop

git checkout develop

git merge --no-ff feature

git push --set-upstream origin develop





