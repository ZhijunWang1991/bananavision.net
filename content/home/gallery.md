---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: 'Gallery'
subtitle: ' '

design:
  columns: '2'

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]
 
gallery_item:
- album = gallery
  image = biplot.png
  caption = Principal component analysis

gallery_item:
- album = "gallery"
  image = "Circle_heatmap.png"
  caption = "Heatmap in circle"
 
gallery_item:
- album = "gallery"
  image = "corr.png"
  caption = "Heatmap to show correlation coefficient"

gallery_item:
- album = "gallery"
  image = "network.png"
  caption = "network analysis"
---
{{< gallery album="gallery" >}} 




