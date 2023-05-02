# Git Retag

1. list all remote tags: `git ls-remote --tags`

2. delete local tag: `git tag -d v2.1.2`

3. push tag deletion to remote: `git push origin :refs/tags/v2.1.2`

4. tag local branch again: `git tag -a v2.1.2 -m "withdrawal flow hotfix"`

5. push tag to remote: `git push origin tag v2.1.2`
