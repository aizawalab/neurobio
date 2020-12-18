+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 7000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "250px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "AIZAWA lab"
  content = "Neurobiology for the brain machinery"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  #overlay_color = "#666"  # An HTML color value.
  overlay_img = "miyajima_unsplash.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Recent news"
  cta_url = "#posts"
  cta_icon_pack = "fas"
  cta_icon = "rss"

[[item]]
  title = "AIZAWA lab"
  content = "Neurobiology for the brain machinery"
  align = "center"

  overlay_color = "#4bb4e3" # An HTML color value.
  overlay_img = "neuron.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.
 
  cta_label = "What we work for"
  cta_url = "#projects"
  cta_icon_pack = "fas"
  cta_icon = "flask"

[[item]]
  title = "AIZAWA lab"
  content = "Neurobiology for the brain machinery"
  align = "center"

  overlay_color = "#4bb4e3" # An HTML color value.
  overlay_img = "dna2.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.
  
  cta_label = "Who we are"
  cta_url = "#people"
  cta_icon_pack = "fas"
  cta_icon = "users"
+++
