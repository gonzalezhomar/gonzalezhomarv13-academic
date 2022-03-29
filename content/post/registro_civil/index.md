---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Oficialias del Registro Civil"
subtitle: "Sí... otro mapa... pero está bonito"
summary: "Sí... otro mapa... pero está bonito"
authors: 
- admin
tags: 
- Python
- Maps
- WebScrapping
- Folium
- Blog
categories: [Blog]
date: 2022-03-29T15:48:56-06:00
lastmod: 2022-03-29T15:48:56-06:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Foto de <a href="https://unsplash.com/@dmjdenise?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Denise Jans</a> en <a href="https://unsplash.com/s/photos/compass?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  "
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Oficialías del Registro Civil

Me gustan los mapas. Son una representación visual simple que todo mundo puede entender, y más si son interactivos. Y este es un problema que me pareció divertido porque [recicle algunas herramientas](https://gonzalezhomar.netlify.app/post/oficinas/) y utilicé algunas [nuevas herramientas](https://nbviewer.org/github/GIScience/openrouteservice-py/blob/master/examples/basic_example.ipynb) (al menos para mí). 

Existen más de 200 oficilías del Registro Civil del Estado de Guanajuato, cómo se puede ver en su [mapa](https://sg.guanajuato.gob.mx/index.php/registro-civil/#oficialiacercana), y existen más de 2000 [puntos de pago](https://finanzas.guanajuato.gob.mx/c_puntos_pago/index.php). Entonces, ¿qué tan cerca están las oficialías de los puntos de pago?

Luego de robarme la información (es un decir, porque es información pública), encontré cómo cruzar 2 bases y para cada punto de una, determinar el punto más cercano en la otra base. Luego utilicé el paquete **open route service** para determinar la ruta más rápida de un punto a otro.

Con lo anterior pude gráficas las 200 oficilías, los puntos de pago más cercano para cada oficialía y la ruta entre ambos. Me gustó el resultado final:

<iframe
    src='./static/oficialias.html'
    width='100%'
    height='500px'
    style='border:none;'>
</iframe>