# Git and Reset Lab

This repository contains the `index.html` project and a record of the Git history exercise.

## Project

`index.html` is a simple page with a heading and a short description.

## Three project commits before the reset

1. `Add starter HTML page`
2. `Add page description`
3. `Add footer`

I used `git log --oneline` to view the history. Before the reset, the three project commits appeared in that order, newest first.

## Reset the latest commit

I used `git reset --hard HEAD~1` to undo the last project commit, then ran `git log --oneline` again. The reset removed `Add footer` from the current branch, leaving the starter page and description commits.

## Compare the versions

The `main` branch shows the final page after the reset, without the footer. Switch to the `before-reset` branch using GitHub’s branch selector to see the page with the footer, representing the third project commit.
