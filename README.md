# Git Command Reference

## Add and Push Code to GitHub Repository

// add in git bash to commit to your repo

cd to/ur/project/path  
```bash
git add .  
git commit -m "Your commit message here"  
git push origin main   # Replace "main" with your branch name if applicable, not required first time  
```
---

## Edit Code from Codespace When Version Lags Behind GitHub

```bash
git fetch origin  
git reset --hard origin/main  
### after second command, check if code is matching to the required GitHub repo  
git pull origin main  
## last command to make permanent change  
```
---

## Check and Remove Remote Repository Connection

# to check which GitHub repo your project directory is connected to 
```
git remote -v  
```
# to remove that old repo from getting connected to that project  
```
git remote remove origin  
```
---

## Add a Local Repository to GitHub (Public Repo)
```
git init  
git add .  
git commit -m "Initial commit"  
git remote add origin https://github.com/username/your-project-name.git  
git branch -M main  
git push -u origin main  
```
