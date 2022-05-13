---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Contaminacion en México"
subtitle: "Otro mapa de la contaminación"
summary: "Otro mapa de la contaminación"
authors: 
- admin
tags: 
- Python
- Maps
- Contaminación
- Blog
categories: [Mapas]
date: 2022-03-09T18:19:26-06:00
lastmod: 2022-03-09T18:19:26-06:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Foto de Maxim Tolchinskiy en [Unsplash](https://unsplash.com/photos/W3y2crFkVIs)"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [Mapas]
---


## Mapa de la contaminación en México

Esta publicación será breve. Navegando por internet me tope con [esta página](http://sinat.semarnat.gob.mx/retc/retc/consulta.php?anio=2019&tipb=1) de la Secretaria de Medio Ambiente y Recursos Naturales (SEMARNAT), que tiene por un lado, el punto geográfico (latitud y longitud) de las empresas contaminantes, y por otro lado, datos de la contaminación en México, por diferentes fuentes, destacando las emisiones al aire, agua, y suelo. 

Considerando la anterior información, utilicé webscrapping para descargar ambas bases de datos, las uní, y tuve la contaminación por punto geográfico. Entonces, con dicha información preparé el siguiente mapa de calor con la contaminación en México:

<iframe
    src='./static/contaminacion.html'
    width='100%'
    height='500px'
    style='border:none;'>
</iframe>
