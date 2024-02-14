---
obsidianUIMode: preview
tags:
  - spells
  - wizard
  - compendium
  - Shadowdark
---
# Wizard Spells

```dataview
TABLE WITHOUT ID
link(file.name, name) AS Spell,
tier AS Tier,
duration AS Duration,
range AS Range
FROM #spell
WHERE contains(class,"Wizard")
SORT tier ASC, file.name ASC
```
^spells-wizard