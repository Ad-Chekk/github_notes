Git Command Reference
Add and Push Code to GitHub Repository

Add in Git Bash to commit to your repo:

cd to/ur/project/path
git add .
git commit -m "Your commit message here"
git push origin main   # Replace "main" with your branch name if applicable (not required first time)

Edit Code from Codespace When Version Lags Behind GitHub
git fetch origin
git reset --hard origin/main


After the second command, check if the code is matching the required GitHub repo.

git pull origin main   # Last command to make permanent change

Check and Remove Remote Repository Connection
# Check which GitHub repo your project directory is connected to
git remote -v

# Remove the old repo from being connected to the project
git remote remove origin

Add a Local Repository to GitHub (Public Repo)
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/your-project-name.git
git branch -M main
git push -u origin main
