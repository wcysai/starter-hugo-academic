---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Display this section immediately before Publications (weight: 60).
weight: 50

title: Preprints
subtitle: ''

content:
  # Display publication entries marked as Preprint / Working Paper.
  filters:
    folders:
      - publication
    publication_type: '3'
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Match the citation format used by the Publications section.
  view: citation
  columns: '2'
---
