# Proof of Work

## Commit History

```text
1e36193 Merge pull request #1 from AbdulAhad176/development
275a5d8 Resolve conflict between development and staging
d3e92d4 Update deployment script for staging
b33822a Update deployment script for development
7ea5c56 Add deployment script and README
b8e6ae7 Initial commit
```

## Reflection Questions

Question	Explain these points in your own words
Q1: Git and GitHub:	Git records changes locally. GitHub hosts repositories online. GitHub provides Pull Requests and collaboration features.
Q2: Three architecture stages:	Working Directory is where you edit files. Staging Area holds changes selected with git add. Local Repository stores commits made with git commit. Explain how your script passed through these stages.
Q3: git stash pop and git stash apply:	Both restore saved changes. apply keeps the stash. pop removes it after successful restoration. If pop causes conflicts, the stash stays.
Q4: git fetch and git pull:	fetch downloads remote updates without integrating them into your current branch. pull fetches and integrates updates. Integration can use merge or rebase. Explain that you used pull after merging the Pull Request.