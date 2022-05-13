---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Farmacias ISSEG"
subtitle: "Un mapa de farmacias ISSEG y de la competencia"
summary: "Un mapa de farmacias ISSEG y de la competencia"
authors: [admin]
tags: [Python, Jupyter, DENUE, ISSEG, farmacias, Folium]
categories: []
date: 2022-05-10T12:34:39-05:00
lastmod: 2022-05-10T12:34:39-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [mapas]
---

## Farmacias en Guanajuato

No es ninguna novedad que me gustan los mapas. Son una representación visual simple, accesible, y si son interactivos, permiten al mismo usuario analizar aquellos puntos que sean de su interés. 

Si bien ya había realizado algunos mapas como el de [oficinas de atención al contribuyente](https://gonzalezhomar.netlify.app/post/oficinas/), el de [medios de pago](https://gonzalezhomar.netlify.app/post/mi-primer-mapa/), y el de [tacos y bares en México](https://gonzalezhomar.netlify.app/post/tacos_y_bares/) para esta ocasión quise combinar 2 tipos de mapas en uno solo.

Con datos de la DENUE, obtuve todas las farmacias del país, por lo que pude puntear aquellas farmacias de la [cadena ISSEG](https://farmaciasisseg.com.mx/#/quienesSomos) que tiene presencia principalmente en Guanajuato, aunque también en Jalisco, Michoacán y Quéretaro, así como todas las farmacias que no son ISSEG en esos mismos estados.

Con ello, en un solo mapa se pueden comparar las farmacias ISSEG y las de la competencia:

<iframe
    src='./static/farmacias_isseg.html'
    width='100%'
    height='500px'
    style='border:none;'>
</iframe>