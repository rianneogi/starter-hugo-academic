---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

active: true

title: Upcoming Talks
# subtitle: 'in Stochastic Optimization'

content:
  # Filter on criteria
  filters:
    folders:
      - event
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: true
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: asc
design:
  # Choose a view for the listings:
  view: community/list_event_modified
  columns: '2'
---
