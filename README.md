## Git Steps in PROG270

- Git/prog270-kimsunmi-2016
- git add README.md
- git commit -m "Modified README in dual repo test"
- git push
- git status

## Git Steps in PROG270 for GitDualRepos

### Step One (status)
- cd ~/temp/qux 
- git status

### Step Two (clone)
- cd ~/Git/prog270-kimsunmi-2016
- git clone git@github.com:username/prog270-kimsunmi-2016.git

### Step Three (edit and push)
- cd ~/temp/qux
- git add README.md or update README at geany
- git commit -m "Modified README in dual repo test"
- git push
- git status

### Step Four (pull)
- cd ~/temp/qux
- git pull
- cat README.md

### Step Five (add AllTest)
- cp -r ~/Documents/AllTest .

### Step Six (pull AllTest)
- git pull

### Step Seven (share Repository)
- Select Settings > Collaborators

Don't every do a git commit without the dash m (-m). 
It opens an editor and you won't be happy when you are in it. 

## Sunmi Kim's Prog270 Repository

There are at least six major programming languages used on the server:

- PHP
- NodeJs
- Python
- Ruby
- C# (ASPX)
- Java

