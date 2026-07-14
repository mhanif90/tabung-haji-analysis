\# Git Bash Cheat Sheet \[As of 6/7/2026]



This cheat sheet contains Git and Git Bash commands that I have learned and personally used throughout my Tabung Haji Analysis project.



\---



**# Navigation**



\## pwd



Shows the current working directory.



\## ls



Lists files and folders in the current directory.



\## cd folder\_name



Move into a folder.



\## cd ..



Move back one directory.



\## cd ../..



Move back two directories.



\## clear



Clears the Git Bash screen.



\# Creating Files and Folders



\## mkdir



Creates a new folder.



\## touch



Creates a new empty file.



\-----



**# Git Commands**



\## git init



Initializes Git tracking for the current project.



\## git status



Shows the current status of the repository.



Useful for checking:



\* Modified files

\* Untracked files

\* Staged files



\## git add .



Stages every modified and new file for the next commit.



Think of it as:



> "Select everything for the next chapter."



\## git add "filename"



Stages only one specific file.



\## git commit -m "filename"



Creates a new checkpoint in the project's history.



The `-m` flag lets me write a short message describing the milestone.



\## git log



Displays the complete commit history.



\## git push



Uploads local commits to GitHub.



\## git config --list



Displays the current Git configuration.



Useful for checking:



\* username

\* email

\* editor

\* default settings



\## git config --global user.name



Sets the Git username.



Example:



```bash

git config --global user.name "Muhamad Hanif"

```



\---



\## git config --global user.email



Sets the Git email address.



Example:



```bash

git config --global user.email "mhanifmnor@gmail.com"

```



\---



\# Concepts I Learned



Git = Local version control system.



GitHub = Online repository for sharing and backing up Git projects.



Repository = The project being tracked by Git.



Working Directory = The files currently on my computer.



Staging Area = Files selected for the next commit.



Commit = A recorded milestone in the project's history.



Branch = A timeline of project development.



master = The current main branch of my project.



HEAD = My current position in the project's history.



origin = The remote repository on GitHub.



origin/master = The latest version stored on GitHub.



\---



\# Workflow I Follow



```text

Create / Edit files

&#x20;       ↓

git status

&#x20;       ↓

git add .

&#x20;       ↓

git status

&#x20;       ↓

git commit -m "Meaningful milestone"

&#x20;       ↓

git push

```



\---



\# Good Commit Messages



✅ Initial project setup



✅ Organize project structure



✅ Explore 2020 annual report



✅ Extract pilgrimage statistics



✅ Clean financial dataset



❌ Update



❌ Fix



❌ Changes



❌ Final final





Coming Soon



git pull

git diff

git restore

git branch

git checkout

git switch

git merge

git clone

git mv

git rm

