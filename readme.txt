Quick setup — if you’ve done this kind of thing before
 Set up in Desktop	or	
 HTTPS
 SSH

https://github.com/zhangzenglei/GitTest.git

We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line

echo "# GitTest" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/zhangzenglei/GitTest.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/zhangzenglei/GitTest.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

张增雷