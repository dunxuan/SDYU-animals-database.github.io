---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ""
subtitle: ""

content:
  # Page type to display. E.g. project.
  page_type: animals

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: 全部
      tag: "*"
    - name: 公告
      tag: 公告
    - name: 三花
      tag: 三花
    - name: 玳瑁
      tag: 玳瑁
    - name: 橘猫
      tag: 橘猫
    - name: 奶牛
      tag: 奶牛

design:
  columns: "1"
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: { padding: [0, 0, 0, 0] }
---
