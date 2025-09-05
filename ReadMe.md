# This is a demo file created to provide an introduction to working with a Git repository.

In this repository, we will explore and practice the core concepts of Git, including:

Initializing a repository

Staging and committing changes

Working with branches

Merging code

Pushing and pulling from remote repositories (GitHub/GitLab/etc.)

Resolving merge conflicts

The purpose of this demo is to help beginners understand version control and collaborative development workflows using Git.
# Getting Started with Git
#  Initialize a Repository
git init


This command creates a new Git repository in your current folder.

 # Configure Git (First-time Setup)
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

 # Check the Status of Your Repo
git status

# Add Files to Staging Area
git add filename.txt
# or to add everything
git add .

# Commit Changes
git commit -m "Initial commit"

# Create a New Branch
git branch feature-branch
git checkout feature-branch

# Merge Branches
git checkout main
git merge feature-branch

# Connect to Remote Repository (GitHub Example)
git remote add origin https://github.com/username/repo.git
git push -u origin main

# Pull Latest Changes
git pull origin main
