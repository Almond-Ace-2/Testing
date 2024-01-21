# Testing
Learning how to Use Git and Github
<br>
This is a break line comment

<br>
ppushh
first Remote commit
Commands 
git clone <link of repository>
NOTTEEE = Always save the file before add push commit
git add <filename>  = Adds changes made to the  File , i.e ready to be commited 
Save ->add ->commit->push
git status          = Status of Repository
git add .           = Add all changes
git commit -m"Some Message" = Commits the changes made to the file
git push origin main = Pushes the changes in the Repository
--------------------------------
make local-> make in github -> add 
<br>
remote ->verify branch and branch
<br>
name -> push the repo by git push origin main
<br>

git init =  Make a local repository of the directory u are in
To push a local repository , we need to have a repository at gihub where we will push
<br>

git remote add origin <-link-> = we have to run this command before pushing the repository
here origin is the nickname we are giving to the repository in our system
<br>

git remote -v = verifying the repository in which we are going to push
<br>

git branch = gives the branch in which u are working in
<br>
git branch -M <new name> = changes the name of the current branch to the new name
<br>

git push -u origin main = it initialises that when we write git push , it will automatically push it to the origin repository's main branch

<br>
git checkout -b <new branch name> = Creates new branch
git checkout <Other branch> = Move from one branch to another
git branch -d <Branch name> = used for deleting a branch ,  will not work if we are on the same branch so first we have to checkout

git diff <branch name> = comparing branches

to merge a branch using github we have to ceate a pull request and then a merge pull request for merging in the branch
git pull origin main = to reflect the changes in the local repository we have to pull


git merge <branch name> =  it merges the branch u are in with the branch name

git reset <filename> = it restores changes for a unstaged file added not commited
git reset = undo all unstaged changes

git reset HEAD~1 = It resets the last commit made
git log = gives timeline

git reset <Hash> = resets the specific commit
git reset --hard<hash> = also resets the changes we made in code in vscode

Forking is just cloning in github , we can make changes and create a new pull request to make changes in the original repository