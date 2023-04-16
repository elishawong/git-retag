# git-retag

- list all remote tags
`git ls-remote --tags`

- delete local tag
`git tag -d v2.0.4`

- push tag deletion to remote
`git push origin :refs/tags/v2.0.4`

- tag local branch again
`git tag -a v2.0.4 -m "new release for v2.0.4"`

- push tag to remote
`git push origin tag v2.0.4`
