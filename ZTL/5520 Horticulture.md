---
type: ZTL
Ztl: 5520
Created: 
alias: Applied Science
Level: 3
Next_Ztl: ""
Status: n/a
Type: ZTL
created: 2023-04-15T20:30
updated: 2024-04-07, 13:01
---
%% 1️⃣ start typing the related ZTL card as the up link (below)%%
up::
%% 2️⃣ Enter the number from the ZTL category into the Ztl YAML above, then a decimal, followed by three digits. Read the table below to see if there is another card with the same number.%%
%%If the dataview query only returns the current file name, good to go!%%
%% Delete after use?%%
Return any files with the same Zettle number:
```dataview
LIST Ztl
FROM !"Templates"
WHERE Ztl = (number(this.Ztl))
```