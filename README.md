[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tbEHDGEc)
# Git and Github Introduction

| Nama  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| Ahamd Syauqi Reza   | PGR | Web Development |

## Early Procedure
1. Install Git
   
```
https://git-scm.com/downloads
```
   
2. Config Git

```
git config --global user.name (your username)
git config --global user.email (your email)
```
3. Setup GitHub
- Create an account on GitHub if you don’t already have one.
- Generate an SSH key for secure authentication:
```
ssh-keygen -t ed25519 -C "your-email@example.com"
```
- Add the SSH key to GitHub:
```
cat ~/.ssh/id_ed25519.pub
```
- Go to GitHub > Settings > SSH and GPG keys, and paste the key.

## Create Repository
- Go to your GitHub account.
- Click New repository.
- Provide a name, description, and choose visibility (Public or Private).
- Optionally, initialize the repository with a README.

or there are 2 options :

a. From local repositories

   1. Initialize
   
 ```
git init
```
2. Add files and commit
```
git add .
git commit -m "Initial commit"
```
3. Link to GitHub 
```
git remote add origin <repository-URL>
```
4. Push 
```
git push -u origin main
```
b. With clone
1. Create a repository on GitHub using the GUI.
Clone it locally
```
git clone <repository-URL>
```
## Push File from Local to Github
```
git push -u origin main
```

## Create New Branch in Github 
1. **Navigate to Your Local Repository**
Open a terminal and go to your repository:

```
cd /path/to/your/repository
```
2. **Create a New Branch**
Use the following command to create a branch:

```
git branch branch-name
```
3. **Switch to the New Branch**
Move to the newly created branch:

```
git checkout branch-name
```

Alternatively, you can combine the steps to create and switch:

```
git checkout -b branch-name
```
Push the New Branch to GitHub
To push the branch to the remote repository:

```
git push -u origin branch-name
```
Verify the Branch
You can list all branches in your repository using:

```
git branch
```
Local Branches: Only on your local machine.
Remote Branches: On GitHub.
## Delete Branch in Github

## Merging Branch in Github

## Other Procedure
