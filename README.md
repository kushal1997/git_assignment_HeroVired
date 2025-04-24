# Graded Assignment: Git and GitHub

## 📘 Overview

This repository `git_assignment_HeroVired` was created as part of a graded assignment to demonstrate Git and GitHub workflows including branching, merging, pull requests, Git LFS, and stash operations.

---

## 🛠 Tech Stack 

- **Language:** Python
- **Version Control:** Git
- **Platform:** GitHub
- **Git Features Used:** Branching, Merging, Pull Requests, Tags, Git LFS, Git Stash
- **Collaboration Tools:** GitHub Collaborators, Code Reviews

---

## ✅ Questions & Implementation Summary



### **Q1: Feature Implementation in CalculatorPlus App**

#### 🔨 Steps Followed:

1. **Created Repository**: `git_assignment_HeroVired`
2. **Branch Created**: `dev`
3. **Initial Code Added**:
    - Basic arithmetic functions: add, subtract, multiply, divide
4. **Tested Code**: All basic arithmatic functions were tested
5. **Merged to Master**: `dev` branch merged to `main`
6. **Created Release**: Tagged as `v1.0`
7. **Collaborator Added**: A classmate added to collaborate on GitHub


#### 🔁 Further Feature Sqrt Workflow

9. **New Branch**: `feature/sqrt` created from `dev`
10. **Square Root Logic Added**
11. **Bug Reported**: In `divide()` method
12. **Fix Applied in `dev`**: 
```python
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b

```
13.  **Pull Request Raised**: `feature/sqrt` ➝ `main`
14.  **Peer Review**: Review requested, feedback applied
15.  **Merged** `feature/sqrt` ➝ `dev`, tested
16.  **Final Merge**: `dev` ➝ `main`
17.  **Release Created**: Tagged as `v2.0`

---

### **Q2: Git LFS Integration**
#### 🔨 Steps Followed:

1. **Created Branch**: `lfs`
2. **Configured Git LFS**:
```bash
git lfs install
git lfs track "*.zip"
```
3. **Added Large File**: Uploaded a file >200MB (e.g., testFile.zip)
4. **Committed & Pushed**: Ensured LFS tracked file properly
5. **Clone Verification**: Cloned repo on another system to validate zip file download

---