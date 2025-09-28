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