…or create a new repository on the command line
echo "# git-github-course" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jefersonrgomes/git-github-course.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/jefersonrgomes/git-github-course.git
git branch -M main
git push -u origin main

#removendo a origem
para ver a origem atualmente vinculada
    git remote -v

para remover a origem atualmente vinculada
    git remote rm origin