# DecodeLabs Internship Git Version Control Project 2

## Overview

This project demonstrates fundamental Git and GitHub version control concepts as part of my DecodeLabs DevOps internship task.

The objective of the project was to learn and apply essential version control workflows, including repository creation, committing changes, branching, merging, and synchronizing code with GitHub.

---

## Project Objectives

* Create a Git repository
* Track file changes using Git
* Commit changes with meaningful messages
* Push code to GitHub
* Create and work on a feature branch
* Merge a feature branch into the main branch
* View and manage commit history
* Understand Git workflow and collaboration fundamentals

---

## Technologies Used

* Git
* GitHub
* Git Bash

---

## Project Workflow

### 1. Repository Creation

A new Git repository was created and connected to GitHub.

### 2. Initial Commit

Project files were added and committed to version control.

```bash
git add .
git commit -m "First project file"
```

### 3. Updating the Project

Changes were made to the project and committed.

```bash
git add .
git commit -m "update homepage message"
```

### 4. Creating a Feature Branch

A separate branch was created to develop a new feature.

```bash
git checkout -b feature-about-page
```

### 5. Committing Feature Changes

Changes were made and committed on the feature branch.

```bash
git add .
git commit -m "Add feature branch content"
```

### 6. Pushing Branch to GitHub

```bash
git push -u origin feature-about-page
```

### 7. Merging Branch into Main

After completing development, the feature branch was merged into the main branch.

```bash
git checkout main
git merge feature-about-page
git push origin main
```

---

## Repository Structure

```text
git-version-control-project/
│
├── index.html
└── README.md
```

---

## Git Commands Demonstrated

```bash
git init
git add .
git commit
git push
git checkout
git branch
git merge
git log --oneline
```

---

## Learning Outcomes

Through this project, I gained practical experience with:

* Version control concepts
* Git branching strategies
* Commit management
* GitHub collaboration workflow
* Repository management
* Branch merging and synchronization

---

---

##Screenshots
### Repository Overview
<img width="1920" height="979" alt="Internship project 2" src="https://github.com/user-attachments/assets/d95fabfe-b854-4a2c-9b10-ca67650d2d18" />


### Commit History
<img width="1044" height="1036" alt="internship project 222" src="https://github.com/user-attachments/assets/91e76d5a-0f4f-4a20-b7bb-9e48afa7edfd" />


### Feature Branch Creation
<img width="1764" height="1012" alt="internship project 22" src="https://github.com/user-attachments/assets/91d72e66-8c8b-4b47-9042-f84eaaa9517a" />


### Merge to Main Branch
<img width="757" height="1029" alt="internship 2222222222222222222222" src="https://github.com/user-attachments/assets/ce04e8d7-6041-474e-a4f6-f83de17f926d" />


---

## Author

Atoyebi Micheal Ademola
DecodeLabs DevOps Intern
