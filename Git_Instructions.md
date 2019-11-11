# Git Instructions

## 1. Make a repository

```
git init
```

```
git clone <url>
```

## 2. Config

```
git config --local user.name
git config --local user.email
```

```
git config --global user.name
git config --global user.email
```

## 3. Create files

```
touch <file name>
```

## 4. Add files to the stage

```
git add .
git add <file name>
```

## 5. Commit files

```
git commit -m "Commit message" -m "Commit description"
```

## 6. Push to remote (name origin)

```
git push origin master
git push <remote name> <branch name>
```

## 7. Add remote

```
git remote add <remote name> <url>
```

## 8. Set new remote URL

```
git remote set-url origin <url>
```

## 9. Create new branch

```
git branch <branch name>
```

## 10. Change branch

```
git checkout <branch name>
```

## 11. Create new and change branch (two commands at once)

```
git checkout -b <branch name>
```

## 12. Merge branch

```
git merge <branch to merge from>
```
