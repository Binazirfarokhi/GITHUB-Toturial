# GITHUB-Toturial
Link to Amandeep video = https://www.loom.com/share/folder/1f60b6729ce94b4ba5cd44a80cc13572

what is Version Control System: 
is a type of tools that helps software development teams manage and track changes to theri source code over time. 

Why do we need VCS? 
1. to keep track who made changes to the code and when, 
2. to revert code back to a perivous state if needed ( like  a time machine) 
3. maintain multiple version of your codes i parallel for different purmoses
4. MOST IMPORTANT REASON : 
Allow multiple developers to work on same code base separately and merge their code changes safely

We have different version control system in the world: 
The most popular one is GIT. 
Git is an open source project available to dl. 
GIT BASIC CONCEPTS: 
Repository: This is the location that all codes are stored. 
Branch : every dev should have their own branch 
create a new branch with CLI ; git checkout -b dev-binazir
then git rebase main : means there is no changes in the main that you need to bring, you have the exact copy of the branch
you will get all the changes reflected on your branch once you do  : git rebase main 
now stage all the changes you made on your branch : git add .     it will add changes 
git commit -m "feature" 
now add all changes to the github : git puch origin dev-binazir 
now all changes added to github 
now you need to create a pull req to add the changes form your branch to main branch.

=========
we call the main branch : stable version of our code in the project
we need another staging or testing branch called development branch to have a testing mode in terms of creating our project. 
===========================
most important git commands 
git init # initialize directory as git repo
git clone url ( from github ) 
git status 
git branch : show which branch you are working on 
git log : show your commit history 
git add .   : stage all your changes , if you want to commit only one wtrite that only -A 
git commit -m "" 
git pull origin main 
git push origin main 
git branch 
git merge develop : will merge develop branch into current one 
git checkout : switch from current to this branch your are working on it 
git branch -m Binazir : will create a new branch and rename it ot this 
git branch -d Biaznr : delete the current page. 
git rm file-name :  remove file from project and stage remove 
git stash : save modified and staged changes
git rebase main : bring the last update of the main branch. 

