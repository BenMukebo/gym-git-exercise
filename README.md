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
git stash pop stash@{1}  
git stash pop stash@{0}
$ git commit -m "Create home and about pages"

$ git stash pop stash@{0} 
$ git reset

=> FAQ: I use `git reset` and `git restore` but I couln't go back to the changes without the team page, did you any command to suggesting me?
```
## Bundle 3

### Exercise 1

```bash
$ git cherry-pick <commit-hash>
$ git cherry-pick 7df7a51d88a177c290d4e84d45114847ec02747a
$ git revert <commit-hash>
$ git revert 7df7a51d88a177c290d4e84d45114847ec02747a
```

### Exercise 2
