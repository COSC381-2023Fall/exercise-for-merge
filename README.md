# exercise-for-merge

## Setup
To set up your repository for this assignment, please run:

```
bash set-up-repo.sh
```

After running set-up-repo.sh, your repository's history should look like:

```
* xxxxxxx (origin/branch2, branch2) Add branch2 to README
| * xxxxxxx (origin/branch1, branch1) Add branch1 to README
|/  
* xxxxxxx (origin/main, origin/HEAD, main) Add set-up script for this assignment.
* xxxxxxx Initial commit
```

## Assignment
This assignment is an exercise for merging. Please do the following merges:

1. Merge branch1 to main, and push main
2. Merge branch2 to main, and push main
3. Merge main to branch1, and push branch1
4. Merge main to branch2, and push branch2

## Expected History
Your repository's history should look like this:
```
*   42c88d7 (HEAD -> main, origin/main, origin/branch2, origin/branch1, origin/HEAD, branch2, branch1) Merge branch 'branch2'
|\  
| * 36f5013 Add branch2 to README
* | 0b8ed44 Add branch1 to README
|/  
* d50678f Update the README for assignment instruction.
* 4157722 Add set-up script for this assignment.
* 3ced79c Initial commit
```