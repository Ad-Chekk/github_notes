To remove any old repo being connected locallly or adding a new repo to be connected locally 
---
```
git remote remove origin 
git remote add origin https://github.com/Ad-Chekk/profile-from-image-13500.git
```
To set the local branch to main 
```
git branch -M main
```
---
To check which remote repo the current files are connected to 
```
git remote -v
```


---
To force your code to the remote repository 
```
git add .
git commit -m "Updated portfolio and removed Lovable branding"
git branch -M main
git push -u origin main --force
```
