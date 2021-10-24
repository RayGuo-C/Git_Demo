# Git_Demo

## Set config values
``` 
git config --global user.name "your name"
git config --global user.email "your email address"
git config --list # Check your basic information
```

## Getting started 
There are two common scenerios   
-  1. Create an empty Git repository or reinitialize an existing one   
   which is used to track our projects   
``` git init ```   
Then, we can list all of files in this directory by   
```ls -la```   

## Before first commit
add gitignore file which is used to ignore some specify files(for example .pyc)  
(we need to write down the Suffix name in the .gitignore file) 
If we want to untract the specified file, we can type:    
```git rest 'file name'```    
Then, we can check it by    
``` git status```

## Our first commit
```git commit -m "initial commit"```
``` git log``` We can see the details of the commits(who submit it and their email)

## Cloning a remote repo
```git clone ../remote_reop.git```
git remote -v 
git brach -A

## After commit 
**Push branch to remote**
```
git branch brach_name
git checkout branch_name # We will switch to this new branch
git branch # See how many branches do you have?


```
git push -u origin 
git remote add origin https://github.com/RayGuo-C/Git_Demo
git branch -a
```

![图片](https://user-images.githubusercontent.com/34149368/138608048-8115bece-0538-4929-ac1f-c4f38da8d079.png)
There are three stages:
1. working directory
2. staging area
3. git repository
