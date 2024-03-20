## Deploy a new version

```bash
reason="New version"
git add -A .
git commit -m "${reason}"
git tag -a v1 -m "${reason}"
git push --follow-tags
```