---

database-plugin: basic

---

```yaml:dbfolder
name: Spell Database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 2
    isHidden: false
    sortIndex: -1
    width: 108
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  tier:
    input: number
    accessorKey: tier
    key: tier
    id: tier
    label: tier
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  duration:
    input: text
    accessorKey: duration
    key: duration
    id: duration
    label: duration
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 196
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  name:
    input: text
    accessorKey: name
    key: name
    id: name
    label: name
    position: 1
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 198
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  range:
    input: text
    accessorKey: range
    key: range
    id: range
    label: range
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  source:
    input: text
    accessorKey: source
    key: source
    id: source
    label: source
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  class:
    input: tags
    accessorKey: class
    key: class
    id: class
    label: class
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 176
    options:
      - { label: "[,Wizard]", value: "[,Wizard]", color: "hsl(225, 95%, 90%)"}
      - { label: "[,Priest]", value: "[,Priest]", color: "hsl(150, 95%, 90%)"}
      - { label: "[,Wizard,Priest]", value: "[,Wizard,Priest]", color: "hsl(7, 95%, 90%)"}
      - { label: "[,Priest,Wizard]", value: "[,Priest,Wizard]", color: "hsl(34, 95%, 90%)"}
      - { label: "Wizard", value: "Wizard", color: "hsl(110, 95%, 90%)"}
      - { label: "Priest", value: "Priest", color: "hsl(224, 95%, 90%)"}
      - { label: "Witch", value: "Witch", color: "hsl(314, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  aliases:
    input: text
    accessorKey: aliases
    key: aliases
    id: aliases
    label: aliases
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 166
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: compact
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /X_Templates
  current_row_template: X_Templates/spell_tmp_prop.md
  pagination_size: 20
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```