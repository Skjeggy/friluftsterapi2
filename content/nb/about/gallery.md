---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 66

title: Gallery
subtitle:

design:
  columns: '2'

gallery_item:
- album: gallery
  image: img1.jpg
  caption: Write your image 1 caption here
- album: gallery
  image: img2.jpg
  caption: Write your image 2 caption here

---

{{< gallery album="gallery" >}}