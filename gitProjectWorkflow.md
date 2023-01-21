---
tags: ["#git" "#gitProject", "versionControl"]
aliases: [""]
author: ["Choi, Hee Joong"]
---

>[!Change Directory (start at the right place)]
>This specific line is for Hee only. Exact address would differ (probably after "Mobile\ Documents")
>> cd ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/HJChoi/ideaBlocks/Semantics\ Proseminar\ Term\ Paper

### 1. Synchronize
#### 1.1. Check for any pull requests
- [GitHub project page](
https://github.com/ychleee/SemanticsProseminarPaper/pulls)
(ychleee / SemanticsProseminarPaper)
- Review and confirm any remaining requests

#### 1.2. If any, pull the main documents
```
git pull https://github.com/ychleee/SemanticsProseminarPaper
```

> [!Warning] 
> This flow from 1.2. to 2.1. is crucial!
> (Otherwise, different commits could get entangled.)
> - Step 1.2. imports any updates;
> - Step 2.1. ensures that future changes start from this updated version (and not any other older versions).

### 2. A new branch for a new day (or for any new version)
#### 2.1. Set a new branch
```
git branch <name>
```
Naming convention: "h0119a", "y0120a", etc.
(First letter of the given name + MMDD + ordered alphabet)

#### 2.2. Checkout to the new one
```
git checkout <name>
```

### 3. You do your job at this stage
Make sure the .md (or any) documents you work in the local folder are worked upon a new branch (set at [[gitProjectWorkflow#2.1. Set a new branch|Section 2.1.]]).

### 4. Ready for share?
#### 4.1. "Save"
```
git add -A
git commit
```
Then, label the commit and exit (ESC => :wq + ENTER)

#### 4.2. Push
```
git push --set-upstream origin <branch name>
```

#### 4.3. Pull requests
- [GitHub project page](
https://github.com/ychleee/SemanticsProseminarPaper/pulls)
- Wait for review from other authors

### 5. Back to [[gitProjectWorkflow#1.1. Check for any pull requests|Section 1.1.]]