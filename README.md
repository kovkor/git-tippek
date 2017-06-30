# git-tippek

#### 1. Adott branch-ben módosult fájlok listája (pl. élesítéshez)
Mikor jött létre a branch?
```
git reflog show --date=iso branchnév | grep 'Created from master'
```
Milyen fájlok változtak azóta?
```
git log --no-merges --name-only --oneline --author=Kornel --since=2017-06-13 branchnév
```


