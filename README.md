## GIT : update commit

### Example

```
7587a25 (HEAD -> my-feat) Commit 3
2cedfec Commit 2
ef87b72 (origin/master, master) Commit 1
```

We want to change the commit 2. Make updates and then :

```
git add -A
git commit --fixup 2cedfec
git rebase 2cedfec^ -i --autosquash
```
