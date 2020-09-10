# Git commands cheat-sheet: the most useful commands

## 1. Navigate to your git project folder

Use `cd` to move between folders. E.g.:

```
cd workspace
cd bdl02_MarianaPantelic_git_cheatsheet
```

## 2. Check the status of the project

I can use this commands **anytime** to inspect my project

- `git status`

    With `git status` I can see if some changes have happened and if some files are ready to be committed.
    It gives me an overview of the project at that specific moment in time.
- `git log`
- `git diff`

## 3. Initializing a git project

If any `git` command that we run shows the following output

> fatal: not a git repository (or any of the parent directories): .git

it means that **we are not inside a git project**.

In this case we can:

1. Make sure that you are in the right folder
2. Initialize a git project, run

```
 git init
 ```

This command creates an empty git repository.
From now on we can make changes to our files and permanently save those changes.


## 4. Save changes

1. `git add .` or `git add -A`

    `git add` tells Git that you want to include the latest changes in the next commit. However, changes are not actually recorded until you run `git commit`.

2. `git commit -m "Meaningful message here"`

    A commit is the Git equivalent of a "save".
3. `git push`.

    This command sends the committed changes to a server. It is used to upload local repository content to a remote repository.




