+++
title = "Instrucciones para ingresar al grupo y usar el cluster."

date = 2019-02-12T00:00:00
lastmod = 2019-03-05T00:00:00
draft = false

math=true


# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Cristóbal Eyzaguirre"]

tags = []
summary = "Como generar contenido"

[header]
image = "headers/getting-started.png"
+++

## Ingreso

Hola! Esta guía asume que has sido invitado formalmente al grupo y detalla los pasos a seguir para estar al día en nuestras notificaciones internas y hacer uso de la infraestructura disponible. Si este es el caso continua leyendo...


| Pasos a seguir |
|---|
| Ingresar a *mailer* |
| Ingresar al Slack grupal |
| Obtener credenciales para Cluster |
| Leer normas |


### Ingresar a *mailer* y *Slack* grupal

El grupo difunde información relevante a una lista de miembros mediante *email*. 
Estas informaciones incluyen el contenido, hora y lugar de las reuniones presenciales entre otras cosas.
El encargado de añadir nuevos miembros es [Hans Lobel](mailto:halobel@ing.puc.cl), haz click en su nombre para enviarle un mail solicitando unirte a la lista.

El [*Slack*](https://slack.com) permite comunicación más fluida entre todos los miembros del grupo.
Al ingresar automáticamente estarás suscrito a los canales *general*, *offtopic*, *almuerzos* y *cluster*.
Otro canales del *Slack* cumplen funciones específicas como el canal *papers* o los de aquellos subgrupos que están trabajando en un proyecto común.
El encargado de añadir nuevos miembros es [Felipe del Río](mailto:fidelrio@uc.cl).

### Obtener credenciales para Cluster

El cluster es una herramienta que puedes utilizar para ayudar tu investigación.
Para comenzar a utilizarlo requieres en primer lugar un *Home*, cosa que puedes solicitar utilizando [este formulario](https://docs.google.com/forms/d/e/1FAIpQLSfbmOJrBAHTIk2atyXRN_vPMGN94Bx7OMLBPAd23ew6xGzh0w/viewform).
Una vez que tengas tu usuario y clave puedes seguir la guia preparada [acá](https://github.com/ialab-puc/cluster) sobre como ingresar y la forma correcta de ingresar trabajos está disponible [acá](https://github.com/ialab-puc/cluster/blob/master/doc/slurm_guide.md).


## Normas y buenas costumbres

{{% alert note %}}
En construccion
{{% /alert %}}

- El espacio de almacenamiento es limitado, evite guardar archivos grandes innecesarios y siempre revise que el dataset no esté antes de descargar uno nuevo.
- El uso del cluster para tareas de ramos no está permitido.
- La administración de tareas en el cluster está automatizada y require presentar los trabajos en un formato *SLURM*. Ingresar trabajos de otra manera perjudica a todos.
- Los recursos solicitados en *Slurm* se reservan hasta que termina el trabajo, dejando a otros posibles usuarios sin poder aprovecharlos. No solicitar más recursos que los necesarios.
