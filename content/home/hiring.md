---
widget: portfolio
headless: true  # This file represents a page section.

# Order that this section appears on the page.
weight: 10

# ... Put Your Section Options Here (title etc.) ...
title: We Are Hiring!

content:
    page_type: job-offers

    # Choose which content to display in the widget
    filters:
        # Folders to display content from
        folders:
            - job-offers
        # Uncomment below to only show content with specific tags:
    #    tags:
    #      - Machine Learning
        exclude_featured: false
        exclude_future: false
        exclude_past: true

design:
    background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
    columns: 2
    # Choose a listing view
    view: 0
    # For Showcase view, flip alternate rows?
    flip_alt_rows: no
---