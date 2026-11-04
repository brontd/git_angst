# README

Practicing The Git Way... 

## Create new branch

```
git checkout -b working_branch main
```


— Create and switch to branch
```git switch -c <new-branch-name> origin/main```

— Create branch but stay in current branch
git branch <new-branch-name>

— Rename branch
```git branch -M main```

— Switch to branch
```git switch main:`

	— Switch branch
	git switch -c main
	git pull

— To push your local development branch to a remote repository, use the standard command: 
	git push -u origin <branch-name>

# Push the updated main branch to your remote repository git push origin main


— OR —

<Make changes>

— Check files
git status

— Stage any modified files
git add .

— Commit changes
git commit -m "Add commit message"

— Switch back to main branch
	git checkout main 
	git switch -c main

— Optional but good to do
	git pull

— Merge development_branch 
	git merge development_branch





# Push the updated main branch to your remote repository
git push origin main

# Safely delete the local feature branch
git branch -d my-feature



-- push file to git hub

git add filename.ext
git commit -m "Add your commit message here"
git push origin main



-- Rename a File

git mv README README.md
 1057  git status
 1058  git push -u origin main
 1059  ls
 1060  git add README.md
 1061  git commit -m "renamed readme to readme.md"
 1062  git push -u origin main





