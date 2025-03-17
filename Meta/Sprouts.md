---
tags:
  - 🌱
  - meta
aliases: 
upstream:
  - "[[Strings Theories]]"
downstream: 
aligned: 
contrasting:
---

 ```dataview
TABLE without id 
out AS "Uncreated files", length(rows) as "Number of Links"
FLATTEN file.outlinks as out
WHERE !(out.file) AND !contains(meta(out).path, "/")
GROUP BY out
SORT length(rows) DESC
LIMIT 20
```
