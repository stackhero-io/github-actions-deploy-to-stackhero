## Deploy a new version

```bash
reason="New version"
git add -A .
git commit -m "${reason}"

# Delete tag if needed
# git tag -d v1
# git push --delete origin v1

git tag -a v1 -m "${reason}"
git push --follow-tags
```