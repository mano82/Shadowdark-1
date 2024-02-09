<% await tp.file.rename(tp.frontmatter.name) %>
 # [[<% await tp.frontmatter.name %>]]

>[!summary]
> *Tier* <% tp.frontmatter.tier %>
> <% tp.frontmatter.class.map(prop => `${prop}`).join(", ") %>
> *Duration*: <% tp.frontmatter.duration %>
> *Range*: <% tp.frontmatter.range %>
> 
> *Source:* <% tp.frontmatter.source %>

<% tp.file.cursor() %>


