# Deploy to production

```console
$ git tag -d production
$ git push origin :stable
$ git tag production [COMMIT HASH]
$ git push origin master
$ git push --tags
```
