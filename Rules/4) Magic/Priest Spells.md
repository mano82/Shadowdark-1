---
obsidianUIMode: preview
tags:
  - spells
  - compendium
  - Shadowdark
  - priest
---
# Priest Spells

```dataview
TABLE WITHOUT ID
link(file.name, name) AS Spell,
tier AS Tier,
duration AS Duration,
range AS Range
FROM #spell
WHERE contains(class,"Priest")
SORT tier ASC, file.name ASC
```
^spells-priest