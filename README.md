# A02 Github And Visual Studio Code Tutorial

**Repository URL format:** `https://github.com/yourUCID/A02`  
Example: `https://github.com/ahhendela/A02`

I'll be making a short step by step tutorial that will help people set up & use **Github** & **VS Code**

---

# Part 1: Step by Step Tutorial (With Github & VS Code)

## 1.) Create a GitHub Account

1. Go to https://github.com/
2. Click **Sign Up**
3. Fill in the appropriate information and verify your email

---

## 2.) Create a GitHub Repository and Name it A02

1. Go to https://github.com/new
2. Name the repository **A02**
3. Choose **Public**
4. Check **Add a README file**
5. Click **Create repository**

---

## 3.) Download and Install Git

1. Download Git from: https://git-scm.com/downloads
2. Install using default settings

---

## 4.) Download and Install Visual Studio Code

1. Download VS Code from: https://code.visualstudio.com/download
2. Install using default settings

---

## 5.) Configure Git

1. Open a terminal (Git Bash on Windows) and run:

git config --global user.name "Your Name"  
git config --global user.email "youremail@example.com"

To then confirm these changes run:

git config --global --list

---

## 6.) Clone the Repository

1. Go to your A02 repository on GitHub
2. Click the green **Code** button
3. Copy the HTTPS URL
4. Open Git Bash and run:

git clone https://github.com/WowFear/A02.git  
cd A02

---

## 7.) Open our project in VS Code

1. Open Visual Studio Code
2. Click File  Open Folder
3. Select the A02 folder

---

## 8.) Now we can stage, Commit and Push our Final Changes

After editing README.md, open the terminal in VS Code and run:

git status  
git add README.md  
git commit -m "Feature: added workflow for using github"  
git push  

---

## 9.) Pull Changes (If Working on Another Computer)

If you are working from another device, update your project by running:

git pull  

---

# Part 2: Glossary

- **Branch**: A separate line of development used to work on changes without affecting the main branch.
- **Clone**: To copy a repository from GitHub to your local computer.
- **Commit**: A saved snapshot of changes in a Git repository.
- **Fetch**: To download updates from a remote repository without merging them.
- **GIT**: A distributed version control system that tracks file changes.
- **Github**: A web-based platform that hosts Git repositories.
- **Merge**: To combine changes from one branch into another.
- **Merge Conflict**: When Git cannot automatically merge changes because the same file was edited differently.
- **Push**: To upload commits from your local repository to GitHub.
- **Pull**: To download and merge changes from a remote repository.
- **Remote**: The online version of a repository (such as GitHub).
- **Repository**: A project folder tracked by Git that stores files and version history.

---

# Part 3: References

Git Official Website: https://git-scm.com/  
Visual Studio Code Official Website: https://code.visualstudio.com/  
GitHub Documentation: https://docs.github.com/  
