# Initial Setup

```sh
cd path/to/your/directory
git init
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
echo "Hello, World!" > hello.txt
git add hello.txt
git commit -m "Add hello.txt with initial content"
git push -u origin master


# Creating and Working with a New Branch


git checkout -b new-branch
echo "This is a new line" >> hello.txt
git add hello.txt
git commit -m "Add a new line to hello.txt"
git push -u origin new-branch


# Undo the last commit or remove the last created file from remote repo using CLI

# Undoing the Last Commit or Removing the Last Created File

git reset --soft HEAD~1
git push -f origin master


## Undo the Last Commit

git reset --hard HEAD~1
git push -f origin master


### Undo the Last Commit but Keep Changes

git rm path/to/your/file
git commit -m "Remove the last created file"
git push origin master


# Git Commands Practice

## Branch Management

### Create a New Branch

Create and switch to a new branch:

```sh
git checkout -b new-branch

git branch

git branch -r

git branch -a

git branch -m new-branch-name

git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

git remote -v

git fetch origin

git push origin master

