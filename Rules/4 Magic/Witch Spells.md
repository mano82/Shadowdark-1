---
obsidianUIMode: preview
tags:
  - spells
  - compendium
  - Shadowdark
  - witch
---
# Witch Spells

```dataview
TABLE WITHOUT ID
link(file.name, name) AS Spell,
tier AS Tier,
duration AS Duration,
range AS Range
FROM #spell
WHERE contains(class,"Witch")
SORT tier ASC, file.name ASC
```
^spells-witch