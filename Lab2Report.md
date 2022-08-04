# CS 235 Lab 2 report 
##### Name : Rukun Aaron , Upi = raar518
## Sections

  - [Notes](#what-is-git)
  - [Reflection](#reflection)
  - [Tasks](#4-debugging-questions-and-exercises)
---
## What is git

- **Git the most popular version control system in the world**
  </br>
  - It record the changes made to our code over type in a database, known as a repository.  
  </br>

- **Instead of manually saving version of a software, git allows us to verision code by doing the following:**
  - Creating a repository  using following command (in our desired repository):   
  ```git
    git init
  ```
  
  - Or going on github (a repository hosting service) and creating a repository and cloning to your local machine using: 
  ```git
  Cloning with HTTPS URLS :
  git clone  https://github.com/Username/Your-Repository.git
  ```
  ```git 
  Cloning with SSH over the HTTPS port
  git clone git@github.com:Username/Your-Repository.git
  ```
  - Add a branch to make your changes:
  ```git
  Create a branch using:
  git branch <branch_name>
  
  Switch to the newly created branch:
  git checkout <branch_name>
  ```
  - After adding our changes we  push the branch to the remote repository:
  ```git
  Stage all changes using:
  git add .

  Commit the changes and write a message using:
  git comming -m <Message>

  Update the rmote repository using 
  ``` 

      