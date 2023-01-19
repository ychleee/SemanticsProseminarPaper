---
tags: ["#git" "#gitProject", "versionControl"]
aliases: [""]
---

>[!Change Directory]
cd ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/HJChoi/ideaBlocks/Semantics\ Proseminar\ Term\ Paper

### 1. Synchronize
#### 1.1. Check for any pull requests
- [GitHub project page](
https://github.com/ychleee/SemanticsProseminarPaper/pulls)
- Review and confirm any remaining requests

#### 1.2. If any, pull the main documents
```
git pull https://github.com/ychleee/SemanticsProseminarPaper
```

### 2. A new branch for a new day (any new version)
#### 2.1. Set a new branch
```
git branch <name>
```
Naming convention: "h0119", "y0120", etc.
(First letter of the given name + MMDD)

#### 2.2. Checkout to the new one
```
git checkout <name>
```

### 3. Ready for share?
#### 3.1. "Save"
```
git add -A
git commit
```
Then, label the commit and exit (ESC => :wq + ENTER)

#### 3.2. Push
```
git push --set-upstream origin <branch name>
```

#### 3.3. Pull requests
- [GitHub project page](
https://github.com/ychleee/SemanticsProseminarPaper/pulls)
- Wait for review from other authors

### 4. Back to [[gitProjectWorkflow#1.1. Check for any pull requests|Section 1.1.]]