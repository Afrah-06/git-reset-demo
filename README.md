# Git and Reset Lab

This repository contains `index.html` and records the Git history exercise.

## Project

`index.html` is a simple page with a heading and a short description.

## Commit sequence before the reset

1. `Add starter HTML page`
2. `Add page description`
3. `Add footer`

I used `git log --oneline` to view the history. Before the reset, the three project commits appeared in that order, newest first.

## Undo the latest commit

The last project commit was undone with:

```text
git reset --hard HEAD~1
```

Then I ran `git log --oneline` again. The reset removed `Add footer` from the current branch, leaving the starter page and description commits.

## Final project state

The `main` branch has the page after the reset. This README was added afterward so the repository link contains the project steps and the reset command.
