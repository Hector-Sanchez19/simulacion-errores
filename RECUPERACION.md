# Recuperación de Archivos en Git

## Error Simulado

Simulé un error al borrar accidentalmente el archivo `errores.sh`.

## Comandos Usados para Recuperar el Archivo

1. Usé `git status` para verificar el estado del archivo eliminado.
2. Usé `git reflog` para obtener el historial de commits recientes y encontrar el commit donde el archivo existía:

Encontré el commit fbcd5fd, donde el archivo aún existía.

#Usé git checkout para recuperar el archivo del commit anterior

`git checkout fbcd5fd – errores.sh`

**¿QUE APRENDÍ?**

Aprendí cómo recuperar un archivo accidentalmente borrado en Git usando herramientas como git reflog y git checkout. Estas herramientas son muy útiles para deshacer cambios no deseados y recuperar archivos perdidos de manera eficiente.

