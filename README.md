## GitHub
### Configuring GitHub
`git --version`  
`git config --global user.name "<USER_NAME>"`  
`git config --global user.email "<EMAIL_ADDRESS>"`  
`git config --global credential.helper store`  
`git config --list`  
### GitHub to Local  
Create a GitHub repository.  
Clone the repository to Local.  
`git clone <HTTPS LINK>`  
### Local to GitHub  
`git init`  
Create a GitHub repository.  
`git remote add origin <HTTPS LINK>`  
`git branch -M main`  
### Check Status of Git  
`git status`  
### Commit & Push  
`git add .`  
`git commit -m "<MESSAGE>"`  
Only first time  
`git push -u origin main`  
Later  
`git push`  
  
OR  
  
If no untracked files  
`git commit -a -m "<MESSAGE>"`  
Only first time  
`git push -u origin main`  
Later  
`git push`
