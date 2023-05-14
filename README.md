# GIT EXERCISES

## Bundle 1

### Exercise 1

```bash
$ git init
$ git branch -M main
echo > file1.txt
$ git add file1.txt
$ git commit -m "Add file1.txt to my project"
$ git remote add origin https://github.com/BenMukebo/gym-git-exercise.git
$ git push origin main 
$ git checkout -b dev
$ git checkout -b test
$ git checkout dev
$ git branch -d test 
```

```bash
$ git add .
$ git commit -m "Copy git commands to my README file"
$ git push origin dev
```

### Exercise 2

```bash
echo > home.html
$ git stash
echo > about.html
$ git stash
echo > team.html
$ git stash
$ git stash list 
git stash drop stash@{1}  
git stash drop stash@{0}
$ git commit -m "Create home and about pages"
```