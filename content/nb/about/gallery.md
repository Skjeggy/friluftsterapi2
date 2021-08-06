---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true
active: true


# Order that this section appears on the page.
weight: 66


design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: "1"

design.spacing:
  # Customize the section spacing. Order is top, right, bottom, left.
  padding: ["40px", "0", "40px", "0"]
 
gallery_item:
 album: album
 image: album/bilde-1.jpg
 caption: Easily add security keys and smartcards to TermBot

gallery_item:
 album: album
 image: album/bilde-2.jpg
 caption: Hardware name and serial number are auto-detected
 
gallery_item:
 album: album
 image: album/bilde-3.png
 caption: PIN Keypad with fallback option to softkeyboard
 
# and more…

---

{{< gallery >}}
