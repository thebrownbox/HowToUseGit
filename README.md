# Basic git commands
Checkout: http://www.hoangvancong.com/category/software-development/tools/git/

## Local commands
#### 1. Initialize a new LOCAL git repository 
```git init``` [_Init in CURRENT FOLDER_]<br/>
```git init NEW_FOLDER```[_Init in NEW FOLDER_]
#### 2. Add a UNTRACKED_FILE or MODIFIED_FILE to staging area
```git add FILE_NAME``` <br/>
```git add .``` [_Add a all changes in CURRENT_FOLDER to staging area_]
#### 3. Check current status
```git status```
#### 4. Commit files in staging area
```git commit -m "your_message"``` <br/>
```git commit -am "your_message"```[_Do both "add" command and "commit" command at the same time_]
#### 5. Show log
```git log```
```git log --oneline```


## Social commands
#### Clone new project
```git clone https://github.com/thebrownbox/HowToUseGit.git```
#### Checkout an exist branch 
```git checkout exist_branch```
#### Create and Checkout a new branch
```git checkout -b new_branch```
#### Merge branch other_branch into current branch
```git merge other_branch```

#### NEW
```command```[_NOTE_]
