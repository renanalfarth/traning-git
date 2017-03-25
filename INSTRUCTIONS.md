# GITHU INSTRUCTIONS - CLAASS

## Initializing

```{r, engine='bash', count_lines}
git init
```

## Config

```{r, engine='bash', count_lines}
git config --global user.name "John Doe"
git config --global user.email "john.doe@myserver.com"
```

## Check changes before commit

```{r, engine='bash', count_lines}
git status
```

## Add and commit

```{r, engine='bash', count_lines}
git add file
git add -A
```

```{r, engine='bash', count_lines}
git commit
git commit -m "Commit message"
```

## View commits

```{r, engine='bash', count_lines}
git show
```

```{r, engine='bash', count_lines}
git log
git log --pretty=oneline
```

```{r, engine='bash', count_lines}
git reflog
```

## Removing and renaming

```{r, engine='bash', count_lines}
git rm file
```

```{r, engine='bash', count_lines}
git mv oldname newname
```

## Ignoring files

```{r, engine='bash', count_lines}
touch .gitignore
```

## Create a branch

```{r, engine='bash', count_lines}
git checkout -b newbranch
```

## Merge a branch in the master

```{r, engine='bash', count_lines}
git checkout master
```

```{r, engine='bash', count_lines}
git merge newbranch
```

## Deleting branch

```{r, engine='bash', count_lines}
git branch -d mybranch
```

## Back to a commit

```{r, engine='bash', count_lines}
git reset --hard e9wewi0iwe09ei0w90ew
```

## Auto resolve conflict

> In a conflict, will always use the master version

```{r, engine='bash', count_lines}
git merge -X ours bugfix
```
> In a conflict, will always use the branch version

```{r, engine='bash', count_lines}
git merge -X theirs bugfix
```
