# GitHub-Tutorial
## create a new repository on the command line 
##(frist time)
echo "# GitHub-Tutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/cronof/GitHub-Tutorial.git
git push -u origin master


##(next time)
git add README.md
git commit -m "first commit"
git push