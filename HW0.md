# Homework 0 - HW0

## Git Branching

### Introduction Sequence
#### Level 1.1

```
git commit
git commit
```

#### Level 1.2

```
git checkout -b bugFix
```

#### Level 1.3

```
git checkout -b bugFix
git commit
git checkout master
git commit
git merge bugFix
```

#### Level 1.4

```
git checkout -b bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```


### Ramping Up
#### Level 2.1

```
git checkout C4
```

#### Level 2.2

```
git checkout bugFix^
```

#### Level 2.3

```
git branch -f master C6
git branch -f bugFix C0
git checkout HEAD^
```

#### Level 2.4

```
git reset HEAD~1
git checkout pushed
git revert HEAD
```


## Screenshot for completed levels
![Completed Levels](/Images/hw0.png)

## Hooks
This animation shows the post-commit hook for a git repository. The `post-commit` script opens the URL https://github.com/gdmannin/HW in the browser
![post-commit script demo](/Images/hw0gif.gif)