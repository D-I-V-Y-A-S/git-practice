# Stages of git
```
1. Modified
2. Staged
3. Commit
```
# Commands
1. git clone {url}

## Give Branch Details
2. git status 

## Commit History
3. git log

## If want to switch back to the previous commit
4. git restore --staged {filename eg.test.txt}

## To switch back to the cloned stage of file
5. git restore {filename eg.test.txt}

## To pull changes
6. git pull origin main/master

## Basic Commands
```
git init
git add .
git commit -m "m stands for message"
git remote add origin {url}
```
### -u stands for --set-upstream as we move from local to branch location. This need to use at 1st time after that no need , just use "git push origin main".
git push -u origin main 

### "git remote" gives default name for the remote repository
git remote 

### "git remote -v" -v means verbose that gives link along with branch for eg origin {url}
git remote -v

## To create branch
git branch -b "{branch_name}
   
   
