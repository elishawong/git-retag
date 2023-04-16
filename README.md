# git-retag

1. list all remote tags
```
git ls-remote --tags
```

2. delete local tag
```
git tag -d v2.0.4
```

3. push tag deletion to remote
```
git push origin :refs/tags/v2.0.4
```

4. tag local branch again
```
git tag -a v2.0.4 -m "new release for v2.0.4"
```

5. push tag to remote
```
git push origin tag v2.0.4
```
