# PREGUNTAS

## ¿QUE ES UN CONTROL DE VERSIONES?

  

El control de versiones, también conocido como "control de código fuente", es la práctica de rastrear y gestionar los cambios en el código de software.

Sin control de versiones, los desarrolladores tienen la tentación de mantener varias copias de código en su equipo. Esto es peligroso porque es fácil cambiar o eliminar un archivo en la copia incorrecta del código, lo que podría perder trabajo.

No se puede hacer seguimiento a la version publicada en produccion.

  

## ¿CUALES SON LOS PROBLEMAS AL NO USAR UN CONTROL DE VERSIONES ?

  

Sin control de versiones, los desarrolladores tienen la tentación de mantener varias copias de código en su equipo. Esto es peligroso porque es fácil cambiar o eliminar un archivo en la copia incorrecta del código, lo que podría perder trabajo.

  

- No se puede hacer seguimiento a la version publicada en produccion.

- No se puede restaurar una version valida previa.

- No se puede analizar los root of cause de los problemas.

  

## ¿CUALES SON LOS BENEFICIOS?

  

- No es necesario estar conectado para guardar cambios.

- Posibilidad de continuar trabajando si el repositorio remoto no está accesible.

- El repositorio central está más libre de ramas de pruebas.

- Se necesitan menos recursos para el repositorio remoto.

- Más flexibles al permitir gestionar cada repositorio personal como se quiera.

  

## ¿QUE TIPOS DE CONTROL EXISTEN?

Podemos clasificar los sistemas de control de versiones atendiendo a la arquitectura utilizada para el almacenamiento del código: locales, centralizados y distribuidos.

  

- **Locales**

Los cambios son guardados localmente y no se comparten con nadie. Esta arquitectura es la antecesora de las dos siguientes.

  

- **Centralizados**

Existe un repositorio centralizado de todo el código, del cual es responsable un único usuario (o conjunto de ellos). Se facilitan las tareas administrativas a cambio de reducir flexibilidad, pues todas las decisiones fuertes (como crear una nueva rama) necesitan la aprobación del responsable. Algunos ejemplos son CVS y Subversion.

  

- **Distribuidos**

Cada usuario tiene su propio repositorio. Los distintos repositorios pueden intercambiar y mezclar revisiones entre ellos. Es frecuente el uso de un repositorio, que está normalmente disponible, que sirve de punto de sincronización de los distintos repositorios locales. Ejemplos: Git y Mercurial.