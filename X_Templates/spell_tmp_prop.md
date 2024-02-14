---
name: <% await tp.file.title %>
aliases:
  - <% await tp.file.title %>
tier: 
class: 
duration: 
range: 
source: Core
tags:
  - spell
System: Shadowdark
obsidianUIMode: preview
obsidianEditingMode: source
---

<%* let str = tp.file.title %>
<%* let str1 = str.replace(/'/g, "") %>
<%* let str2 = str1.replace(/ /g, "-") %>

<% await tp.file.move("Compendium/Spells/"+str2) %>

```button
name Apply Style
type append template
action spell_template
remove true
color green
```
^button-applySpellTemplate