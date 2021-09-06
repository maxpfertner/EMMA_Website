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

## Herzlich Willkommen auf der IAA vom Projekt EMMA - *Ein multi- und intermodales Erreichbarkeitsmodell für Arbeitsstandorte*

Arbeitsstandorte sind prägend für unseren Alltag. Wo unser Arbeitsplatz liegt, hat Einfluss auf unser Mobilitätsverhalten - und zwar nicht nur für den Weg zur Arbeit, sondern auch für andere Erledigungen und Freizeitaktivitäten. Wegeketten (wie Arbeiten – Einkaufen – Kind abholen – nach Hause) werden davon dominiert, wie man den Weg zur Arbeit zurücklegt. Fährt man morgens mit dem Auto in die Arbeit, ist es sehr wahrscheinlich, dass man alle weiteren Wege des Tages ebenfalls im Pkw zurücklegt. Arbeitet man nun an einem Standort, der schnell und komfortabel nur mit dem Auto erreichbar ist, wird zwangsweise das gesamte Mobilitätsverhalten davon dominiert. Ziel moderner Planung in Metropolregionen sollte es daher sein, dass rein autoabhängige Arbeitsstandorte vermieden werden, um diesen „Lock-in“ Effekt zu verhindern und sich die Beschäftigten am Standort für verschiedene Verkehrsmittel – je nach individueller Eignung und Präferenz – entscheiden können.

In EMMA, unserem DFG-geförderten Projekt (2019 – 2021), wird die Perspektive der Unternehmensstandorte eingenommen und die multimodale Erreichbarkeit von Arbeitskräften aus Arbeitsstandortsicht modelliert – das heißt, wir berechnen vereinfacht gesagt wie viele Menschen innerhalb gewisser Zeitbeschränkungen (z.B. 30 Minuten) mit verschiedenen Verkehrsmitteln (ÖPNV, Pkw, Fahrrad, sowie Kombinationen davon wie Bike+Ride) diesen Standort erreichen können. Dabei geht es uns bewusst nicht um die tatsächlich Beschäftigten, sondern wir verwenden die erreichbare Bevölkerung als einen Indikator dafür, wie gut der Standort erreichbar ist. Dahinter steht das Prinzip der „Erreichbarkeitsplanung“, welches zunehmend die rein mobilitätsbasierte Planung ablöst. Es geht dabei darum, dass das Wechselspiel aus Stadtstruktur und Verkehrssystem so optimiert wird, damit eine Vielzahl von möglichen Zielen (z.B. Supermärkte, Ärztinnen, Schulen, Restaurants, …) für möglichst viele Bürgerinnen und Bürger erreichbar ist, anstatt nur Reisezeiten zwischen (potenziell bedeutungslosen) Zielen zu verbessern.

Ein beispielhaftes Zwischenergebnis dieser Analysen ist der Vergleich der erreichbaren Bevölkerung innerhalb von 30 Minuten mit verschiedenen Verkehrsmitteln:

{{< figure src="/post/img/vergleich.gif" title="Verkehrsmittel im Vergleich" lightbox="true" >}}

 
Wie Sie sehen, schwankt die Anzahl der erreichbaren Bevölkerung sehr stark. Im ÖPNV („PT)“ sieht man deutlich die Achsen des schienengebundenen Verkehrs und die Zentren der Region weisen die höchsten Werte auf. Flächendeckend erreicht das Auto die höchsten Werte – die weißen Flecken auf der Karte sind zwar mit dem Pkw nicht erreichbar, fallen aber nicht ins Gewicht, da diese buchstäblich im Wald oder auf dem freien Feld liegen. Deutlich wird auch, dass die Kombination aus ÖPNV und Fahrrad dort ihre Vorteile ausspielen kann, wo Arbeitsstandorte relativ nah am schienengebundenen ÖPNV liegen, jedoch zu weit entfernt, um zu Fuß zu gehen. Hier könnte eine Förderung von Bike and Ride am meisten Potenzial entfalten.
Eine weitere wichtige Erkenntnis aus dieser (im Arbeitsstand befindlichen) Analyse ist auch das Potenzial der Zentren außerhalb Münchens, wie z.B. Augsburg, Ingolstadt, Landshut, Rosenheim, etc. Im Modell schneiden diese oft sehr gut ab und auch die Fahrraderreichbarkeit ist im Vergleich zum Pkw recht hoch, da sich die Bevölkerung auf eine recht kompakte Stadtstruktur konzentriert. In Verbindung mit Mobilitätsbefragungen deutet dies ein Potenzial für eine weitere Förderung des Radverkehrs an, insbesondere für Menschen, die in diesen Zentren wohnen und arbeiten.
Eine große offene Frage bleibt aber natürlich, wann ein Arbeitsstandort „gut liegt“. Zahlen und Modellergebnisse helfen uns, diese Frage zu beantworten. Mindestens genau so wichtig ist aber auch Ihre Meinung – wir würden uns freuen, wenn Sie uns ein paar Worte dazu hinterlassen, wodurch sich Ihrer ganz persönlichen Meinung nach ein guter Arbeitsstandort auszeichnet:



---------------------------------
### Get in touch with us!
Are you are researcher working on similar topics? A planner who is open to test new methods? A company who has to make a location choice?  
We are always open to cooperate and exchange with you. Don't hesitate to email us!






