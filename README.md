# Git Cheat Sheet

### Initialization
- **Initialize a new Git repositorty:**
  - git init `repository_name`
  - ``git init [or] git init C:\Users\user\repoName``
- **Clone an existing repository:**
  - git clone `repositorty_url`
  - ``git clone https://github.com/sulemanshaik013/git-learning``
### Configuration
- **Configure Your Name:**
  - git config --global user.name `"Your_Name"`
  - ``git config --global user.name "Suleman"``
- **Configure Your E-mail:**
  - git config --global user.email `"Your_Email"`
  - ``git config --global user.email "suleman@mail.com"``
- **Show configuration settings:**
  - ```git config --list```
### Basic Commands
- **Check Repository Status:**
  - ```git status```
- **Add Changes to Staging Area(index):**
  - Add a specific file
    - ```git add file.txt```
  - Add all changes in the current directory
  	- ```git add .```
- **Commit Changes:**
  - git commit -m ``<"your commit message">``
  - ```git commit -m "added README.MD"```
- **View Commit History:**
  - ```git log```
- **Push Changes to Remote Repository:** 
  - git push origin ``<branch name>``
  - ```git push origin master```
- **Pull Changes from Remote Repository:** 
  - git pull origin ``<branch name>``
  - ```git pull origin master```
### Branching
- **List Branches:**
  - ```git branch```
 - **Create a new Branch:**
   - ``` git branch <feature-branch>``` 
   - ``` git checkout -b  <feature-branch>``` 
- **Switch between Branches**
  - ```git checkout <branch-name>```
 - **Merge a Branch into Current Branch:**
   - ```git merge <branch-name>```
 - **Delete a Local Branch:**
   - ```git branch -delete <branch-name>``` 
   - ```git branch -d <branch-name>```
   - ```git branch -delete -force <branch-name>```
   - ```git branch -D <branch-name>``` 
   
   Note`-D Shortcut for --delete --force`
   
- **Delete a Remote Branch:**
   - ```git push origin -delete <branch-name>```
   - ```git push origin -d <branch-name>```
   - ```git push origin -delete -force <branch-name>```
   - ```git push origin -D <branch-name>```

### Viewing Changes

- **View the differences:**
  - To see changes that are not staged: ```git diff```
  - To see changes that are staged: ```git diff -staged```
  - To view differences between branches: ```git <branch_one> <branch_two>```
  - Display detailed information about a specific commit: ```git show <commit>```
    
