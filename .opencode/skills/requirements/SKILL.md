---
name: requirements
description: update requirements
---

## What I do
- Read the imports from all notebook and list them out.
- If in plan mode, list all the imported requirements.
format your output like this
```md
# a.ipynb
- list 1
- list 2

# b.ipynb
- list 1
- list 2
```
- If in build mode, ask user to use the TT3L_G01_Notebook.ipynb imports only or all the notebooks imports.
- If the existing requirements.txt is same as the notebook imports, there is no changes needed.
- If there is existing requirements.txt, make a backup as requirements.txt.old (you can overwrite the existing backup).
- Combine all the imports into requirements.txt that pip can digest.


## When to use me
- When human ask you to update the requirements.
