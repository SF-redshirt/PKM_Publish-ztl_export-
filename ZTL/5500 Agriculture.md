---
type: ZTL
Ztl: 5500
Created: 
aliases:
  - Applied Science
Level: 2
Next_Ztl: ""
Status: n/a
Type: ZTL
up: "[5000 Applied Science](5000%20Applied%20Science.md)"
created: 2023-04-15T20:29
updated: 2024-04-07, 12:44
---

Return any files with the same Zettle number:
```dataview
LIST Ztl
FROM !"Templates"
WHERE Ztl = (number(this.Ztl))
```