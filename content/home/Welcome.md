+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

#title = "EMMA"
# subtitle = "**E**mpowering **M**ulti**m**odal and Intermodal **A**ccessibility Analysis // **E**in **m**ulti- und intermodales Erreichbarkeits**m**odell für **A**rbeitsstandorte"


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
  # image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
 
[header]
image = "headers/banner.png" #the image path is header/...jpg
caption = "Image credit: [**Academic**](https://github.com/gcushen/hugo-academic/)"
 
+++


Within the project EMMA, we are building a **multimodal and intermodal accessibility model** for workplace locations in the metropolitain region of Munich, enabling new analysis that will contribute to a better regional understanding and planning of workplace locations and their impacts on the daily commute of its workers.

EMMA is a [DFG-funded project](https://gepris.dfg.de/gepris/projekt/401093473?context=projekt&task=showDetail&id=401093473&) at the [Chair of Urban Structure & Transport Planning](https://www.bgu.tum.de/en/sv/homepage/) at [Technical University of Munich](www.tum.de/en). It is part of the [Research Group Accessibility Planning](https://www.linkedin.com/company/tum-accessibility-planning/) at the Chair.  

### Our Accessibility Model

The model is **multimodal** in a sense that we look at the most important modes of transport in parallel (Public Transport, driving, cycling, and walking). It is also **intermodal**, because our methodology allows the analysis of combined trips, such as *Bike&Ride*, which play an increasingly important role in times of the intruduction of new mobility services that aim at *complementing* public transport rather than *replacing* it.

### Tools & Data

EMMA is built 100% on open source tools. We use
- [OpenTripPlanner](https://www.opentripplanner.org/) for routing and isochrone calculations
- [PostGIS](https://postgis.net/) to store and query our spatial data
- [R](https://www.r-project.org/) & [RStudio](https://rstudio.com/) for scripting, data analysis, and putting it all together.

Open data is the foundation of our analysis. Mainly
- [OpenSteetMap](https://www.openstreetmap.org/) for all road networks
- [Official nationwide GTFS-data](https://www.opendata-oepnv.de/) provided by "OpenData-Plattform ÖPNV", following the [European Delegated Regulation 2017/1926 of 31 May 2017](https://eur-lex.europa.eu/eli/reg_del/2017/1926/oj)


---------------------------------
### Get in touch with us!
Are you are researcher working on similar topics? A planner who is open to test new methods? A company who has to make a location choice?  
We are always open to cooperate and exchange with you. Don't hesitate to email us!






