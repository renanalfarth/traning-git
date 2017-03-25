# GITHUB INSTRUCTIONS

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
