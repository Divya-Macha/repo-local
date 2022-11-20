#demo
Some description
#demo about creating a repository locally and making the git recognise it
create a folder eg:demo-repo-local
create a file named README.md in it
make sure you get out of any directories and your are particularly in the demo-repo-local directory
so now inorder to push the local repository to the remote repository,
we need to initialise git to the repository
=> git init
=> git status
=> git add .
=> git commit -m "added readme.md of demo-repo-local"
// directly pushing it using "git push origin main/master would give us an error because the git deosn't know where to push it on github
so we create a repository on git hub and and now in the terminal type
" git remote add origin 'git@github.com#############.git'";(from the code section of your newly created repository)
we can check any remote repositories available thatwe have conneced to our repository
=> git push origin main/master //(OR We can use git push -u origin main/master inorder to just use gitpush from the next time you would want to push your files)
