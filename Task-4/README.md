# Simulating and Resolving Merge Conflicts

## Objective

- Create a scenario that produces a merge conflict and resolve it

## Tasks Performed

### 1. Creating Branches

- Created two branches from the same commit using:
  - `git branch branch1`
  - `git branch branch2`
- Switched between branches with `git checkout branch1` or `git checkout branch2`

### 2. Modifying Files

- Edited the same line(s) in a common file on both branches to simulate conflict

### 3. Merging Branches

- Attempted to merge branches using `git merge branch-name`
- Observed merge conflict messages

![output](images/1.png)

![output](images/3.png)

### 4. Resolving Conflicts

- Used `git status` to see conflicting files
- Used `git diff` to review differences
- Manually resolved conflicts in the files
- Added resolved files with `git add` and committed the merge

![output](images/2.png)

## Outcome

Successfully created and resolved a merge conflict while understanding how to identify and fix conflicting changes in Git.
