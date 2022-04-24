---
pageTitle: "List Git Conflicts"
---

Ever needed to list all the conflicted files in your repo after attempting a merge?

```
git diff --name-only --diff-filter=U
```
