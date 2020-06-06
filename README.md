# Git Learnings

git init

git add &lt;file&gt;

git rm &lt;file&gt;

git restore &lt;file&gt;

git status

git log

git commit -m "message"

# What we are going to learn today?

gitignore 
- By default, each and every folder is under git tracking.
- To indicate git, that certain files/folders need not be tracked, we need to use gitignore
- To create ignore files, we need to create a file named ".gitignore" without any file extension 
- Why to ignore files/folders? To avoid tracking of temporary files/folders that can be regenerated.

git remote
- To enable github integration, there by publishing our code in the public domain
- git remote add origin https://github.com/SaravanaKumarKJ/LearnGit.git

git push
- git push -u {to_location} {from_location}
- git push -u origin master

Repository => folder
D:\Playground\git-learning\LearnGit (my local system) => https://github.com/SaravanaKumarKJ/LearnGit.git (Remote Github)