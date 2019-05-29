+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.

[[item]]
  title = "Current Research"
  content = "Comsol Multiphysics Modeling of 1D Josephnson Junction"
  align = "right"
  
  overlay_color = "#333"  # An HTML color value.
  overlay_img = "coolplot.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
 
   # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "View GitHub"
  cta_url = "https://github.com/irisdorn/automatedcomsol"
  cta_icon_pack = "fas"
  cta_icon = "book"
  
  # [[item]]
  # title = "Learn Physics"
  # content = "Materials to Be Posted Soon"
  # align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  # overlay_img = "lisart.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Materials"
  # cta_url = "irisdorn.com/physicsmaterials.html"
  # cta_icon_pack = "fas"
  # cta_icon = "book"

[[item]]
  title = "Data Mining"
  content = "Python Notebooks"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "data.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "View Kernels"
  cta_url = "http://www.kaggle.com/irisdorn/kernels"
  cta_icon_pack = "fas"
  cta_icon = "book"

+++
