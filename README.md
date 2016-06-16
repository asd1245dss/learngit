# Git Tutorial

## Create Git Repository 

1. ```powershell
   git init
   ```

2. ```powershell
   git add file
   ```

3. ```
   git commit -m "your comment"
   ```

## Version Controll

1. ```powershell
   git status
   ```

2. ```powershell
   git diff file
   ```

   ​

## Commiter Profile

1. ```powershell
   git config --global user.name "Your Name"
   ```

2. ```powershell
   git config --global user.email youremail@example.com
   ```

3. ```powershell
   git commit --amend --author="yourname<youremail@example.com>" -m "your comment"
   ```

   ​

## Version Reset

1. ```powershell
   git reset --hard commit_id
   ```

2. ```powershell
   git reflog
   ```

   ​

## Restore Amend

1. ```powershell
   git checkout -- file
   ```
2. ```powershell
   git reset HEAD file
   ``
   ```
## Delete File

1. ```powershell
   git rm file
   ```

2. ```powershell
   git commit -m "Your comment"
   ```

## Add Remote Git Repository

1. ```powershell
   git remote add origin Your Remote Repository
   ```

2. ```powershell
   git push -u origin master
   ```

   ​

## Clone Remote Git Repository

1. ```powershell
   git clone Your Remote Repository
   ```

   ​

## Create And Merge Branch

1. ```powershell
   git checkout -b Your Branch
   - git branch Your Branch
   - git checkout Your Branch
   ```

2. ```powershell

   ```

   ​