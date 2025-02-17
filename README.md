# Git Commit States

Git tracks files in three main states: **Untracked**, **Staged**, and **Committed**.

## 1. Untracked State  
A file is **untracked** when it exists in the working directory but has not been added to Git. This means Git does not track any changes made to the file.
## 2. Staged	
The file is added to the staging area and ready to be committed.
## 3. Committed	
The file is saved permanently in the repository.

# Importance of Git History in Version Control and Debugging

## **1. What is Git History?**
Git history is a record of all commits made in a repository. It helps track changes, identify when and why modifications were made, and revert to previous versions if needed.

## **2. Why is Git History Important?**

### 🔹 **Tracking Changes**
- Git history allows developers to see who made changes, when they were made, and what was modified.
- Helps maintain accountability and collaboration in teams.

### 🔹 **Debugging Code**
- If a bug appears, you can check past commits to identify when the bug was introduced.
- Use `git bisect` to find faulty commits by performing a binary search in the commit history.

### 🔹 **Reverting to Previous Versions**
- If an update breaks the application, you can roll back to a stable version using:
