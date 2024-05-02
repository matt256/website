---
title: "Git Command Quick Reference"
date: 2024-02-17T21:01:42-06:00
draft: false
---

This is a compilation of the commands that I can never remember of the top of my head and dont want to google to find the right article for. 

#### Default rebase conflicts to theirs
```bash {class="my-class" id="my-codeblock" lineNos=inline tabWidth=2}
git rebase -X theirs <branch_to_rebase_onto>
```
#### Set or reassign git remote tracking branch

```bash {class="my-class" id="my-codeblock" lineNos=inline tabWidth=2}
git branch current_branch --set-upstream-to origin/<remote_branch_name>```
```

