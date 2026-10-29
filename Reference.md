# Add files

git add <fileName>
git add .

# Remove files from stage to Working directory

git restore --cached <file path>

# commiting Change

git commit -m '<commit message>'

# for commit and adding the ONLY modified file

git commit -a

# it will open new shell tab for me it's nano and then you insert your commit message!

#

# the faster way to give commit meesage is this:

git commit -am '<message>'

# to change the previous commit message

git commit --amend
git commit --amend -a

# all gitlog cheats

git log -> <for all logs>
git log -n 3 -> <the last 3 message>
git log --grep="searching" -> <searching by the desc of the commit>
git log --oneline" -> <showing the logs in one line (pretty and clean)>
git log --graph" -> <showing in nice graphical format>
git log filename. -> <showing the logss of the file>
