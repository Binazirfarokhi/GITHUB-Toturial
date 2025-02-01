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
now you need to create a pull req to add the changes form your branch to main branch
