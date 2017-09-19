# hello-world
My first Github repository

Programming in C++:
 - Compile: g++ -o helloworld hello-world.cpp
 - Execute: ./helloworld 

Programming in Java:
 - Compile: javac MyProgram.java
 - Execute: java MyProgram

Git command
 - git status
 - git log
 - git pull --rebase
 - git add test.txt: track the file "test.txt" in git
 - git commit -m "commit message"
 - git commit --amend
 - git branch: list all branches
 	- git branch test: create a new branch named "test"
 	- git checkout test: switch to the "test" branch
 	- git branch -d test: delete the local branch
 	- git push -d origin test: delete the remote branch
 - git cherry-pick <commit-hash>: choose a commit from one branch and apply it onto another
 	- git checkout master: switch to the branch (here it's master) you want apply the commit to 
 - git push