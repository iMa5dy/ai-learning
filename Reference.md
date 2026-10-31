# Add files to stage

git add <fileName>
git add .

# Remove files from stage to Working directory

git restore --cached <file path>

# commiting Change

git commit -m '<commit message>'

# for commit and adding the ONLY modified file

git commit -a

 <!-- it will open new shell tap and then you insert your commit message! -->

# way to give commit and adding :

git commit -am '<message>'

# to edit the previous commit message

git commit --amend
git commit --amend -a

<!-- -a here is add  -->

# log

git log<!--          --><show all logs>
git log -n 3<!--    --> <show he last 3 in small message>
git log --grep="search" <searching by the desc of the commit>
git log --oneline<!----><showing the logs in one line (pretty and clean)>
git log --graph"<!-- --><showing in nice graphical format>
git log filename.<!----><showing the logs of the file>

# reset / undo chagnes

git reset --soft HEAD~1 <!----><back to previous commit and keep in state area>
git reset --mixed HEAD~1<!----><back to previous commit and keep in working directiory>  
git reset --hard HEAD~1 <!----><back to previous commit and remove EVERYTHING of that commit >

 <!-- HEAD~x is just a number you can type any number!! -->

git checkout <filename > <discard changes on working directory>

git revert <commit hash> <undo changes in the commit hash by adding a new commit, this keep in history>

# diff

git diff <!--         --><show what has been change (stage vs working)>
git diff --staged <!----><show what has been change (stage (&& ||) working vs last commit)>
