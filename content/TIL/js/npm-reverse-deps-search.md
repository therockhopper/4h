---
pageTitle: "NPM Reverse search Dependencies"
---


I specifically wanted to find what package used a dependency that was breaking an initial install. This may help somebody out trying todo the same:
```
find ./node_modules/ -name package.json | xargs grep <the_package_name>
```
