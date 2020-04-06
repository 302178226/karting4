# maintain git project

git checkout -b <branch_name>

//make changes in project here

git add .

git commit -m "description of changes"

git checkout master

git branch -d <branch_name>

# upload changes

git push origin master

# [how to upload git project](https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)

cd karting4

git init

git add .

git commit -m "First commit"

git remote add origin <remote repository URL>
  
git remote -v
  
git push origin master
 
