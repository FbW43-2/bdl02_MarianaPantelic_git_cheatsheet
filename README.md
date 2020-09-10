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

    Messages given bu `git status`:
    - > working tree clean

        This means that no change had happened in our project since our last `git commit`

    - > nothing to commit

        This means that no `git add` has happened yet, so there is no change to commit

    - > Changes to be committed

        This means that we have staged some changes with `git add` and now we need to commit

    - > changes not staged for commit

        This means that we need to use `git add .` to prepare some changes to be committed

- `git log`

    This command shows the commit logs.

- `git diff`

    Shows what changes have happened in our project since the last `git add .`.
    - Lines marked in **red** are lines that were removed.
    - Lines marked in **green** are lines that were added.



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




