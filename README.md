### Git Exercises

1. Initialize and set name of the primary branch
```
git init
git branch -m main
git add .
git commit -m "initial commmit"
```
2. See status, log, branch and add README.md
````
git status
git status -s
git status --short
git log
git log --oneline
git branch -a
git add README.md
git commit -m "add README.md"
````

3. Create project on GitHub

4. Install Git Credential Manager
on mac
```
brew install --cask git-credential-manager
```
5. Push to remote
```
git push -u origin main
```
6. Update README.md
```
git add README.md
git commit -m "update README.md after pushed to remote"
git push
````
