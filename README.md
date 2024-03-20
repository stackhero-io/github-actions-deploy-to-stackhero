# GitHub Action to deploy Node.js, Python, PHP and more to Stackhero

See [https://www.stackhero.io/en/stackhero/documentations](https://www.stackhero.io/en/stackhero/documentations)


## Deploy a new version

```bash
reason="New version"
git add -A .
git commit -m "${reason}"
git tag -a v1 -m "${reason}"
git push --follow-tags
```