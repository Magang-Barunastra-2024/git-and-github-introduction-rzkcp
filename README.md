[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tbEHDGEc)

# Git and Github Introduction

| Nama              | Division | Sub-Division     |
| ----------------- | -------- | ---------------- |
| Ahmad Syauqi Reza | PGR      | Web Develeopment |

## Early Procedure

1. Install Git

```
https://git-scm.com/downloads
```

![My Image](image/install.png)

2. Config Git

```
git config --global user.name (your username)
git config --global user.email (your email)
```

When its done, it will have user name and user gmail saved like this

![My Image](image/config.png) 3. Setup GitHub

- Create an account on GitHub if you don’t already have one.
- Generate an SSH key for secure authentication:

```
ssh-keygen -t ed25519 -C "your-email@example.com"
```

- Copy the SSH key using this command line:

```
clip < ~/.ssh/id_ed25519.pub
```

![My Image](image/ssh.png)

- Go to GitHub > Settings > SSH and GPG keys, and paste the key.

![My Image](image/addssh.png)

## Create Repository

- Go to your GitHub account.
- Click New repository.
- Provide a name, description, and choose visibility (Public or Private).
- Optionally, initialize the repository with a README.

**Or there are 2 options using local file :**

a. From local repositories

1.  First, make sure you have a folder with the same name as repository,Then Initialize on git bash

```
git init
git remote add origin (your SSH repository-URL)
get branch -M main
```

2. To check if local folder same with Github folder, write this command line

```
git pull origin (branch name)
```

b. Git clone

```
git clone (your SSh repository-URL)
```

![My Image](image/clone.png)

## Push File from Local to Github

1. Make sure your folder has a file to be upload on Github
2. Enter this command line on Git Bash

```
git add.
git commit -m "write the description"
git push -u origin main
```

![My Image](image/push.png)

## Create New Branch in Github

1. Create a New Branch
   Use the following command to create a branch:

```
git checkout -B (branch name)
```

2. Switch to the New Branch
   Move to the newly created branch:

```
git checkout (branch name)
```

3. To push the new branch to GitHub, you can use this command line

```
git push -u origin branch-name
```

4. To see al branches in your repository, write this command line :

```
git branch
```

![My Image](image/newbranch.png)

## Delete Branch in Github

1. Make sure you are in another branch that you want to delete by writing this command line

```
git checkout (branch name)
```

2. Write this command line to delete the branch

```
git branch -d (branch name)
```

![My Image](image/deletebranch.png)

## Merging Branch in Github

1. Move to the branch that you want to merge with (for example main branch) with this command line :

```
git checkout (branch name)
```

2. Merge the branch that you selected with this command line

```
git merge (branch name that you selected to merge)
```

![My Image](image/merge.png)
