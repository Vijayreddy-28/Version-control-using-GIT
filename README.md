# Using .gitignore and Tracking Files

## Objective

- Set up a `.gitignore` file to exclude specific files or directories
- Verify that ignored files are not tracked by Git

## Tasks Performed

### 1. Creating .gitignore File

- Created a `.gitignore` file
- Added patterns to ignore files such as:
  - Log files (`*.log`)
  - Temporary files (`*.tmp`)
  - Other unnecessary directories/files

### 2. Testing Ignore Rules

- Added files that match the ignore patterns
- Added files that do not match the ignore patterns

### 3. Verifying Tracking Status

- Used `git status` to check which files are being tracked
- Confirmed that ignored files were not listed or tracked by Git

![output](images/1.png)

![output](images/2.png)

## Outcome

Successfully configured `.gitignore` to exclude unwanted files and verified proper file tracking in the repository.
