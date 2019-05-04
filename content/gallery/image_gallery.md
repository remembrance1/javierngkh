+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Image Gallery"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image = "./javierngkh/static/img/headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
 
[[gallery_item]]
album = "gallery"
image = "https://www.youtube.com/embed/oVw_koOnTDA?ecver=1&amp"
caption = "Dark theme"

[[gallery_item]]
album = "gallery"
image = "https://raw.githubusercontent.com/remembrance1/javierngkh/blob/master/videoplayback.mp4"
caption = "Dark theme"
+++

{{% alert note %}}
Under Construction

{{% /alert %}}

Welcome to the **personal demo** of Academic. Other demos available include:

- [**Project Demo** (Academic's actual site)](https://sourcethemes.com/academic/)

**Over 100,000 [Amazing Websites](https://sourcethemes.com/academic/#expo) have Already Been Built with Academic**

**[Join](https://sourcethemes.com/academic/docs/install/) the Most Empowered Hugo Community**

{{% alert note %}}
Under Construction
{{% /alert %}}

{{< gallery album="gallery" >}}

