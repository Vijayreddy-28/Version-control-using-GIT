# Undoing Changes and Reverting Commits

## Objective

- Experiment with undoing changes in the working directory and commits

## Tasks Performed

### 1. Undoing Changes in Working Directory

- Modified a tracked file
- Used the following commands to discard changes:
  - `git checkout -- <file>`
  - `git restore <file>`

  ![output](images/1.png)

  ![output](images/2.png)

### 2. Undoing Commits

- Created a commit after making changes
- Used different commands to undo commits:
  - `git revert <commit-id>`
  - `git reset <commit-id>`

  ![output](images/3.png)

  ![output](images/4.png)

  ![output](images/5.png)

## Key Differences

### git restore / git checkout -- <file>

- Used to discard changes in the working directory
- Does not affect commit history

### git revert

- Creates a new commit that undoes the changes of a previous commit
- Safe to use in shared/public repositories

### git reset

- Moves the HEAD pointer to a previous commit
- Can modify or remove commit history
- Types:
  - `--soft`: Keeps changes staged
  - `--mixed`: Keeps changes but unstaged
  - `--hard`: Deletes changes completely

## Outcome

Successfully learned how to undo file changes and commits using different Git commands and understood when to use each approach.
