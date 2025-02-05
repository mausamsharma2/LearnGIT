# LearnGIT
Anyone with this can learn basic GIT <br>
Author - Mausam Sharma   // to show if how updating a file work

Git Configuration:

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"


Basic commands for GIT:
git clone <-link-> : clone the repo
git status : display status of code

git add <-link-> : apply changes in the files
git add . : apply changes in all the files

git commit -m "some meaningfull message related to code" : the record of change

git push origin main : to push your code to the remote(Github) repository

created index.html and now we are going to push it into our repository

git checkout : to go to another branch
git checkout -b <-branch name-> : creates and switch to new branch
get checkout -d <-branch name-> : deletes the named branch

(Branch: git creates a copy to the same code for you to add some changes in the branch and not let you effect the original branch)

git push origin feature1(or any branch name you are pushing will be pushed in the directory)

git remote -v (Lists all remote URLs connected to your local repository.)

git log --oneline --graph --decorate --all (Shows a compact commit history.)

# WORKFLOW
 # Initialize Git
git init

# Add a remote GitHub repo
git remote add origin https://github.com/your-username/learnGIT.git

# Check status and add files
git status
git add .
git commit -m "Initial commit"

# Push to GitHub
git push origin main

# Work on a new feature
git checkout -b new-feature
git add .
git commit -m "Added a new feature"
git push origin new-feature

# Merge feature into main
git checkout main
git merge new-feature

# Pull latest changes from GitHub
git pull origin main
