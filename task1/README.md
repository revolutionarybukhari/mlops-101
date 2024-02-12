# Task1

This is a Python project for demonstrating Git branching and project scaffolding.

## Git Commands

### Create branches:

```bash
git checkout -b dev
git checkout -b test
git checkout -b master
git checkout -b Husnain



mkdir task1
cd task1
touch README.md
touch requirements.txt
mkdir src
touch src/main.py
mkdir tests
touch tests/test_main.py
```
# My Project

This is a MLOPS task1 .

## Git Commands

### Creating Branches
```bash
# Create dev branch
git checkout -b dev

# Create test branch
git checkout -b test

# Create master branch
git checkout -b master

# Create anusha branch
git checkout -b anusha

# pushing created branches
git push origin dev
git push origin test
git push origin master
git push origin anusha


git checkout anusha
mkdir task1
cd task1


type nul > main.py

rest files were were made in VS code 


git status 
# Add changes to staging area
git add .

# Commit changes
git commit -m "Commit message"
git push origin  anusha 

git checkout dev
git merge anusha
git add .
git commit -m "Merge branch 'anusha' into dev"
git merge an
