+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = "6500"

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome to IU!"
  content = "Join our virtual welcoming event on"
  content = "Wednesday, September 23, 1-2:30pm ET"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "slider_crimson_shine.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.25  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Register here"
  cta_url = "https://iu.co1.qualtrics.com/jfe/form/SV_efKiH4jy7cKtMgt"
  cta_icon_pack = "fas"
  cta_icon = "users-class"

[[item]]
  title = "Looking for an accountability group?"
  content = ""
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "slider_work.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Check our weekly virtual working group sessions :woman_technologist:"
  cta_url = "post/work-group/"
  #cta_icon_pack = "fas"
  #cta_icon = "users-class"

[[item]]
  title = "Meet your fellow postdocs!"
  content = "We host virtual recurring social events. :coffee: :beer: :tea: :wine_glass:"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "slider_social.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Check our calendar"
  cta_url = "calendar/"
  #cta_icon_pack = "fas"
  #cta_icon = "users-class"
  
[[item]]
  title = "Get involved"
  content = ""
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "slider_committees.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.25  # Darken the image. Value in range 0-1.
  
  cta_label = "Explore our committees"
  cta_url = "committees-webpage/"
  #cta_icon_pack = "fas"
  #cta_icon = "users-class"
  

+++
