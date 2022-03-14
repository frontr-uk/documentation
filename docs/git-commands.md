Delete all branches that have been merged

```
git branch --merged | egrep -v "(^\*|master|main|dev)" | xargs git branch -d
```
