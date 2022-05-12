---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tacos y bares en México"
subtitle: "Mapas con todos los bares y taquerías en México"
summary: "Mapas con todos los bares y taquerías en México"
authors: 
- admin
tags: 
- Python
- Maps
- DENUE
- Datashader
categories: [Maps]
date: 2022-03-16T15:27:20-06:00
lastmod: 2022-03-16T15:27:20-06:00
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

## Mapas con todos los bares y taquerías en México

Esta publicación será breve. Navegando por internet me tope con el siguiente par de tweets:

{{< tweet 1494801927015747587 >}}

{{< tweet 1499768947675217923 >}}

Si bien, puedo replicar dicho mapa usando el paquete de Folium quise experimentar con otras herramientas; ello porque he tenido problemas con *Folium* para usarlo en una cantidad grande de puntos. A su vez, eso me hizo recordar el siguiente mapa:

{{< tweet 1190798529309986816 >}}

Por lo anterior, si alguien puede hacerl para la Ciudad de México y para León, Guanajuato, ¿por qué no replicar el mapa de bares, pero para todo México usando los datos de la DENUE de INEGI? El siguiente mapa es resultado de lo anterior, y lo hice con *Datashader*:

<iframe
    src='./static/graph.html'
    width='100%'
    height='500px'
    style='border:none;'>
</iframe>

Y ya estando en esas, replique el mapa de tacos, con los tacos y torterías también usando los datos de la DENUE de INEGI:

<iframe
    src='./static/tacos.html'
    width='100%'
    height='500px'
    style='border:none;'>
</iframe>