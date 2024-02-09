# [[<% tp.file.title %>]]

Costo: **<% tp.frontmatter.cost %>**
Slot equipaggiamento: **<% tp.frontmatter.slots %>**
AC: **<% tp.frontmatter.AC %>**
Proprietà: 
<% tp.frontmatter.properties.map(prop => {
  const [ability, description] = Object.entries(prop)[0];
  const formattedAbility = `* *${ability}*. ${description}`;
  return formattedAbility;
}).join("\n") %>
# Descrizione
<% tp.frontmatter.Description %>

# Note


---
<% tp.frontmatter.System %>
<% tp.file.creation_date('DD/MM/YY') %>
