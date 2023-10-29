# git-github
## 1. Basic settings
- set user name
```
git config --global user.name 'yourname'
```
- set email
```
git config --global user.email 'youremail'
```
- check the settings
```
git config --list
```
## 2. Create a new repository
- create in local
```
mkdir xxx
cd xxx
git init
```
- clone from github
```
git clone https://github.com/yuanma0427/git-github.git
```
## 3. Create a new file
- use vi, touch, etc; or create directly in local
- check status
```
git status
```
- submit to staging area
```
git add xxx
```
- check status
- submit to git repository
```
git commit -m 'description'
```
- check status
## 4. Edit file
**same as creating the file**
- edit the file, check status, submit to staging area, check status, submit to git repository, check status
## 5. Remove file
- remove the file
```
rm (-rf) xxx
```
- remove the file from git
```
git rm xxx
```
- commit
```
git commit -m 'description'
```
## 6. Update to remote git repository
- update
```
git push
```
    
