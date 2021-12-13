# Assignment 5 and 6

## Reactivating Jupyter

```sh
# first, cd into your coding/ directory
% cd coding/assignment_05

# activate your virtualenv
% pyenv activate lecture_06-3.8.5

# run jupyter lab
% jupyter lab
```


## Adding, committing, and pushing changes to GitHub

### To see a list of changes:

```sh
% git status
```

### How to add all new and changed files
```sh
% git add . # add ALL files that are unstaged
```

### How to add a single file
```sh
% git add readme.md # add a single file (e.g. just readme.md) if it was not staged for commit
```

### Write a commit message

After adding your file(s), you need to write a commit message:

```sh
% git commit -m "your commit message goes here; a summary of changes"
```

### Push to GitHub

After that, you push your changes to GitHub

```sh
% git push origin main
```