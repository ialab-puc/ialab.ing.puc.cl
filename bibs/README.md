# Documentación de bibliografía de sitio de IALab

Las publicaciones de IALab se muestran en el siguiente enlace: http://ialab.ing.puc.cl/publications/.
Se utiliza la herramienta BibBase (https://bibbase.org/) para embeber en el sitio las publicaciones presentes en el archivo `pubs.bib`, que se encuentra en la raíz de la rama `master` del repositorio del sitio.

Para actualizar el archivo `pubs.bib` con nuevas publicaciones es necesario seguir los siguientes pasos:

- Agregar, eliminar o actualizar los archivos individuales que se encuentran en la carpeta `bibs`.
- Dentro de la carpeta ejecutar `make pubs` para actualizar `pubs.bib`. Es necesario tener instalada la herramienta `bib-tool` de forma local.
- Agregar los cambios, commitear y pushear hacia Github.


