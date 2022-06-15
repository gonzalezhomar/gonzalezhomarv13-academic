---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Líneas del Optibus"
subtitle: "Jugando con la api de Mapbox"
summary: "Jugando con la api de Mapbox"
authors: [admin]
tags: [Mapbox, Mapas, HTML, León, Optibus]
categories: []
date: 2022-06-15T12:38:39-05:00
lastmod: 2022-06-15T12:38:39-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Ruta 1 del Optibus"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [mapas]
---

## Mapa de l Optibus

Como me gustan los mapas, me pareció muy interesante encontrar esta notebook, donde se hace [un análisis de la ciudad de Paris](https://nbviewer.org/github/uber/h3-py-notebooks/blob/master/notebooks/urban_analytics.ipynb). De manera muy particular, me pareció interesante replicar el mapa de la ruta 18:

![imagen](./static/mapa.png)

Así que utilizando ese ejemplo y la api de [Mapbox](https://www.mapbox.com), para la cual me regitré hace mucho tiempo, replique el mismo mapa para la ruta 1 troncal de las líneas del [Optibus](https://www.leon.gob.mx/movilidad/articulo.php?a=93) en código HTML:

<iframe
    src='./static/rutas.html'
    width='100%'
    style='border:none;'>
</iframe>