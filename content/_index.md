---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: collection
    content:
      title: Publications
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
  - block: awards
    content:
      title: Media
      username: admin
    
---
