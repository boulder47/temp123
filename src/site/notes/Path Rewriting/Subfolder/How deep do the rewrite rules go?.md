---
{"dg-publish":true,"permalink":"/path-rewriting/subfolder/how-deep-do-the-rewrite-rules-go/","created":"2024-05-07T10:12:25.000-05:00","updated":"2024-05-07T10:12:25.000-05:00"}
---

With the rewrite rules: 

```
Path Rewriting:
Subfolder:subfolder-rewritten
Path Rewriting/Subfolder:this-will-never-hit
```

Will this file be in folder `subfolder-rewritten` or in `Subfolder`?

It should be in Subfolder as "matching exits on first hit"