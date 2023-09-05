### get hosted did.json

```shell
curl -o did-output.json -H "Host: yurenju.github.io" http://localhost:3332/did-web/did.json
```

### Publish did.json

```shell
git checkout publish
git show main:did.json > did.json
git add did.json
git commit -a -m 'update did.json'
git push origin publish
git checkout main
```
