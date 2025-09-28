# Learning Git 🎮

## Config Username and Email
To set your global username in Git, use the following command:
```bash
git config --global user.name "Pheng Mengheak"
git config --global user.email "pmengheak@gmail.com"
```
## Config branch
To switch to main branch
```bash
git config --global init.defaultBranch main
git branch -m master main
```
## Push local to cloud repo
```bash
git remote add origin link_repo_cloud(github or gitlab)
git push -u origin main
```

## Create Branch
To create branch and switch branch
```bash
git branch branch-name
git checkout branch-name
```
To create and automatic switch to that branch
```bash
git checkout -b branch-name
git push --set-upstream origin branch-name
git branch new-branch-name source-branch
```
By doing this you'll create new branch and then copy the entire code and then you edit that code and then you push to to public repo and then set-upstream will create new branch on github and the main branch(DevOps team) will take a look and compare and then If success they will confirm and merge!