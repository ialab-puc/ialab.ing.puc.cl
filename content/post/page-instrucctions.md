+++
title = "Instrucciones Pagina"

date = 2018-08-28T00:00:00
lastmod = 2018-08-28T00:00:00
draft = true

math=true


# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Cristobal Eyzaguirre"]

tags = []
summary = "Como generar contenido"

[header]
image = "headers/getting-started.png"
+++

## Posts

Escribir un Post es facil usando markdown.
Lo primero es la metadata:

~~~
+++
title = "Titulo del Post"

date = 2018-08-27T00:00:00
lastmod = 2018-08-27T00:00:00

authors = ["Bob Smith", "David Jones"]

# pueden ser "action-recognition", "xai", "meta-learning", "robotics", "vqa"
# o el nombre de cualquier otro archivo en content/lines-of-research/ 
tags = ["vqa", "robotics"]

summary = "Descripcion corta que aparece en las previsualizaciones, eg. el widget"

[header]
image = "url/relativa/a/content/img/"
+++
~~~

El resto es escribir markdown usando el sabor kramdown. Existe una guia [aca](http://www.mit.edu/~k2smith/post/writing-markdown-latex/)

Con `math=true` en la metadata avisamos que se usara latex en el documento.

{{% alert note %}}
math=true debe ir antes de [header]
{{% /alert %}}

~~~
$$\left [ – \frac{\hbar^2}{2 m} \frac{\partial^2}{\partial x^2} + V \right ] \Psi = i \hbar \frac{\partial}{\partial t} \Psi$$
~~~
$$\left [ – \frac{\hbar^2}{2 m} \frac{\partial^2}{\partial x^2} + V \right ] \Psi = i \hbar \frac{\partial}{\partial t} \Psi$$

